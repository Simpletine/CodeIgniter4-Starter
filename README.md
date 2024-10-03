# CodeIgniter4 Starter

[![Official Website](https://img.shields.io/badge/Official_Website-Visit-yellow)](https://simpletine.com)  
[![YouTube Channel](https://img.shields.io/badge/YouTube_Channel-Subscribe-FF0000)](https://www.youtube.com/channel/UCRuDf31rPyyC2PUbsMG0vZw) 

## Overview
This repository provides a starter template for **CodeIgniter 4**, configured to get your application up and running quickly. Follow the instructions below to set up and start developing with CodeIgniter 4.

## Prerequisites
Ensure you have the following installed before starting:

- **PHP 7.4** or above
- **Composer**
- **CodeIgniter 4.4.8**

## Installation Guide

### 1. Clone the Project
Choose one of the following methods to clone the project into your desired folder:

**Using Composer:**
```bash
composer create-project simpletine/codeigniter4-starter starter --stability=dev
```

**Or using Git:**

```bash
git clone https://github.com/Simpletine/CodeIgniter4-Starter.git starter
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

## Code Standards and Fixing
This project follows PHP coding standards. To automatically fix coding standard issues, run the following command:

```php
composer run fix
```

## Troubleshooting
If you encounter any issues during installation, feel free to open a discussion in the community.

