# Changelog

## [4.7.0] - 2026-03-21
### Added
- Introduced compatibility updates for CodeIgniter 4.7.0.

### Changed
- Updated `README.md` to reflect new installation instructions and prerequisites:
  - PHP version requirement updated to `>= 8.2`.
  - Composer version requirement updated to `>= 2.0`.
  - Removed Git-based installation instructions.
- Adjusted `App.php` configuration:
  - Simplified `permittedURIChars` to exclude Unicode character classes.

### Removed
- Deprecated support for PHP versions below 8.2.
