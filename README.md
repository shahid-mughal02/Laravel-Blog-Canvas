# Laravel Blog Canvas Template

## Laravel Installer Globally Setup
```
composer global require laravel/installer
```

## Install Laravel Project
```
laravel new project_name
```

## Install Blog Canvas
```
composer require austintoddj/canvas
```

## Publish Assets and Primary Configuration Files
```
php artisan canvas:install
```
> Visit
http://127.0.0.1:8000/canvas/login
Email: email@example.com
Password: password

## Create a Symbolic Link to Ensure File Uploads Accessible Publicly
```
php artisan storage:link
```

## Beautiful Frontend Canvas UI
```
php artisan canvas:ui
```
> Visit
http://127.0.0.1:8000/canvas-ui

## Install Packages
```
npm install
```

## Run Project NPM
```
npm run dev
```

## Run Project Artisan
```
php artisan serve
```

## Features
- [x] Manage Users
- [x] Roles: Editor, Contribution, Admin
- [x] Manage Posts
- [x] Post SEO
- [x] Tags & Topics
- [x] Statistics
- [x] Dark/Light Mode
- [x] Multi Language
