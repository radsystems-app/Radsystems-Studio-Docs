---
title: System Requirement
description: 
published: true
date: 2021-12-17T14:35:45.733Z
tags: 
editor: markdown
dateCreated: 2021-08-03T03:09:09.844Z
---

# System Requirements
**System requirements** will vary on what application you want to create.

## Operating System
- Windows x86/x64 (Windows 7, 8, 10, 11)
https://www.microsoft.com/en-us/software-download/

## Database
- MariaDB - https://mariadb.org/download/
- MySQL - https://dev.mysql.com/downloads/installer/
- SQLite - https://www.sqlite.org/download.html
- PostgreSQL - https://www.postgresql.org/download/
- MSSQL Server - https://www.microsoft.com/en-us/sql-server/sql-server-downloads

## PHPRad Classic
- PHP - https://www.php.net/downloads.php
- Composer - https://getcomposer.org/download/

> Please note that when you want to download **NodeJS**, it should be the **Long Term Support(LTS)** version.
{.is-info}

## PHPRad Vue
- NodeJS - https://nodejs.org/en/download/
- VueJS - `npm install -g @vue/cli`
- Quasar - `npm install -g @quasar/cli`
- PHP - https://www.php.net/downloads.php
- Composer - https://getcomposer.org/download/

## NodeRad Vue
- NodeJS - https://nodejs.org/en/download/
- VueJS - `npm install -g @vue/cli`
- Quasar - `npm install -g @quasar/cli`

## PyRad Vue
- NodeJS - https://nodejs.org/en/download/
- VueJS - `npm install -g @vue/cli`
- Quasar - `npm install -g @quasar/cli`
- Python - https://www.python.org/downloads/windows/
- pip - https://www.geeksforgeeks.org/how-to-install-pip-on-windows/
> **RadSystems** will auto-detect needed packages and ask you to install upon opening the **RS** window such as:
{.is-success}
- flask
- flask-wtf
- flask-sqlalchemy
- marshmallow-sqlalchemy
- flask-bcrypt
- flask-cors
- flask-mail
- flask-jwt-extended
- pymysql

## ASPRad Vue
- NodeJS - https://nodejs.org/en/download/
- VueJS - `npm install -g @vue/cli`
- Quasar - `npm install -g @quasar/cli`
- .Net SDK 3.1 - https://dotnet.microsoft.com/download/dotnet/3.1

## Mobile Build With Quasar
- Visit [Quasar Docs](https://quasar.dev/quasar-cli/developing-cordova-apps/preparation#-add-cordova-quasar-mode)

# Others
> You can use <a href="https://www.apachefriends.org/download.html">XAMPP</a> or <a href="https://laragon.org/download/index.html">Laragon</a>. It has already PHP, MySQL/MariaDB and PhpMyAdmin to manage databases.
{.is-info}

> Webserver such as Apache or Nginx is not required.
{.is-info}

# Setup Environment Variable Path
Some installations need to manually encode their parent folder in Windows Environment variables (e.g php.exe, python and pip)
1. Go to **Start->Control Panel**
2. **System and Security**
3. **System**
4. **Advance system settings**
5. **Environment Variables**
![1.png](/requirements/1.png)
6. In the **User variables** and **System Variables** , click variable **Path**
7. Click **Edit**
8. Click **New**
![2.png](/requirements/2.png)
9. Enter the following path below: (*Note: This is the path in my computer, yours is different*)
- `D:\xampp2\php` (*This is the path of my php.exe*)
- `%localappdata%\Programs\Python\Python39` (*This is the path of my python.exe*)
- `%localappdata%\Programs\Python\Python39\Scripts` (*This is the path of my pip.exe*)
- `%programfiles%\dotnet` (*This is the path of my dotnet.ext*)
10. Click Okay
11. Restart your computer if needed.
![3.png](/requirements/3.png)
