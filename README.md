Basic App
=========

Basic App is a free, open-source, self-hosted CMS platform based on the CodeIgniter 4 PHP Framework.

Basic App is designed to provide a quick start for sites made on CodeIgniter 4 and to take over the implementation of the basic functions of a modern web application.

## System Requirements

- PHP 7.2 or later
- MySQL or MariaDB
- Composer
- Apache or Nginx

## Installation

### Step 1

Create new application using Composer:

    composer create-project --stability=dev --keep-vcs --prefer-dist basic-app/basic-app demoapp
    
The command installs the application in a directory named `demoapp`. 
You can choose a different directory name if you want.

### Step 2

Configure url, timezone, and database connection settings in the `/.env` file.

### Step 3

Execute commands via shell:

```
php spark migrate -all
php spark install
php spark seeder
```

### Step 4

Set domain document root to `/public` directory.

## Backend

Access application backend in your brower by opening: `http://example.com/admin`
```
login: admin
password: admin
```
