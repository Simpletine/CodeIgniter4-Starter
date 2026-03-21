# CodeIgniter4 Starter

[![Official Website](https://img.shields.io/badge/Official_Website-Visit-yellow)](https://simpletine.com)  
[![YouTube Channel](https://img.shields.io/badge/YouTube_Channel-Subscribe-FF0000)](https://www.youtube.com/channel/UCRuDf31rPyyC2PUbsMG0vZw) 

## Overview
This repository provides a starter template for **CodeIgniter 4**, configured to get your application up and running quickly. It is based on [Simpletine/CodeIgniter4-HMVC-Shield](https://github.com/Simpletine/CodeIgniter4-HMVC-Shield), with pre-designed standardized configurations for modules. This starter aims to enhance project initialization efficiency and will gradually expand with more functional features.

## Prerequisites
Ensure you have the following installed before starting:

- **PHP ≥ 8.2**
- **Composer ≥ 2.0**
- **CodeIgniter ≥ v4.4.0**

## Installation Guide

### 1. Clone the Project
Use Composer to create the project in your desired folder:

```bash
composer create-project simpletine/codeigniter4-starter starter --stability=dev
```

**Navigate to the project folder:**
```bash
cd starter
```

### 2. Update Dependencies
Run the following commands to update dependencies and copy required files:

```bash
composer update
cp vendor/codeigniter4/framework/public/index.php public/index.php
cp vendor/codeigniter4/framework/spark spark
```

### 3. Set Up Environment File
Copy the .env file to the root directory:

```bash
cp env .env
```

### 4. Start the Application
Run the app using the built-in server. If you want to use a custom port (e.g., 9000), specify it using the --port option:

```php
php spark serve --port=9000
```

The application should now be accessible at http://localhost:9000.

## Differences from `composer create-project codeigniter4/appstarter`

This starter is distinct from the default `composer create-project codeigniter4/appstarter` in the following ways:

1. **HMVC Support**: Based on [Simpletine/CodeIgniter4-HMVC-Shield](https://github.com/Simpletine/CodeIgniter4-HMVC-Shield), it includes pre-designed standardized configurations for modules.
2. **Enhanced Setup Efficiency**: Pre-configured settings and structures to streamline project initialization.
3. **Future Expansion**: Plans to gradually integrate more functional features to further enhance development efficiency.

## Code Standards and Fixing
This project follows PHP coding standards. To automatically fix coding standard issues, run the following command:

```php
composer run fix
```

## Troubleshooting
If you encounter any issues during installation, feel free to open a discussion in the community.

