---
title: System Requirement
description: 
published: true
date: 2022-05-09T12:42:34.203Z
tags: 
editor: markdown
dateCreated: 2021-08-03T03:09:09.844Z
---


> **System requirements** will vary on what application you want to create.
{.is-warning}

# Operating System
Radsystems Studio currently supports only the **Windows Operating System(OS)**, **Windows x86/x64 (7, 8, 10, 11)**. You can download the OS from the <a href="https://www.microsoft.com/en-us/software-download/" target="_blank">Microsoft Website</a>. For those using other operating systems, you will need to install a **Virtual Machine (VM)** and then install the supported windows OS to that **Virtual Machine (VM)** in order to install **Radsystems Studio** in it.
- <a href="https://www.virtualbox.org/wiki/Downloads" target="_blank">VirtualBox (MacOS, Linux, Solaris)</a>
- <a href="https://wiki.winehq.org/Download" target="_blank">Wine (Linux, MacOS, Android)</a>
- <a href="https://www.parallels.com/" target="_blank">Parallels Desktop (MacOS)</a>
- <a href="https://www.vmware.com/products/fusion.html" target="_blank">VMWare (MacOS, Linux)</a>
- <a href="https://www.codeweavers.com/crossover/" target="_blank">CrossOver (ChromeOS, MacOS, Linux)</a>

These are just a few options out there.
# Development Servers
The recommended development server for Radsystems Studio is <a href="https://laragon.org/download/" target="_blank">Laragon</a>. <a href="https://laragon.org/download/" target="_blank">Laragon</a> gives the option to install multiple versions of <a href="https://www.php.net/" target="_blank">PHP</a>, <a href="https://nodejs.org/en/" target="_blank">NodeJS</a>, <a href="https://www.python.org/downloads/" target="_blank">Python</a>, etc.

## Database
**Radsystems Studio** currently supports 4 database types, (<a href="https://mariadb.org/download/" target="_blank">MariaDB</a> or <a href="https://dev.mysql.com/downloads/installer/" target="_blank">MySQL</a>), <a href="https://www.sqlite.org/download.html" target="_blank">SQLite</a>, <a href="https://www.postgresql.org/download/" target="_blank">PostgreSQL</a>, and <a href="https://www.microsoft.com/en-us/sql-server/sql-server-downloads" target="_blank">MSSQL Server</a>.

## Backend Framework (API)
Backend Frameworks are the aspect of the project that runs and is executed on the server.

### PHP - Laravel
The **PHP -  Laravel** framwork depends on mostly PHP and Composer for package management. But if you download and install the <a href="https://laragon.org/download/" target="_blank">Laragon</a> full setup, you are ready to develop a **Laravel, Boostrap & jquery(PHPRad Classic)** project.

If you choose to install just php and composer, then you can download them from the links below:
- <a href="https://www.php.net/downloads.php" target="_blank">PHP</a>
- <a href="https://getcomposer.org/download/" target="_blank">Composer</a>

### NodeJS - Express
The **NodeJS - Express** framwork depends on **NodeJS version 10** and above, but it is recomended you use **NodeJS version 14** or any of the **<a href="https://nodejs.org/en/" target="_blank">Long Term Support(LTS)</a>** versions. Once it is installed, you are ready to use the **NodeJS - Express** backend framework.
> Please note that, It is recomended you download any of the **<a href="https://nodejs.org/en/" target="_blank">Long Term Support(LTS)</a>** versions.
{.is-info}

### Python - Flask
The **Python - Flask** framwork depends on **Python 3**, but it is recomended you use **<a href="https://www.python.org/downloads/release/python-3810/" target="_blank">Python 3.8</a>** Once it is installed, you are ready to use the **Python - Flask** backend framework.

### ASP .Net Core
The **ASP .Net Core** framwork depends on **<a href="https://dotnet.microsoft.com/en-us/download/dotnet/3.1" target="_blank">.NET Core 3.1</a>** Once it is installed, you are ready to use the **ASP .Net Core** backend framework.

## Frontend Framework (UI)
These are the frameworks used for generating the HTML, CSS and JavaScript for the projects.

### Vue Quasar
The **Vue Quasar** framwork depends on **NodeJS version 10.18.1**, **Quasar CLI**. It is recomended you use **NodeJS version 14** version. After installing **NodeJS**, you can install **Vue Quasar CLI** using `npm i -g @quasar/cli`, if you dont and you try to create a project, **Radsystems Studio** will prompt you to intsall it.

### PrimeVue
The **PrimeVue** framwork depends on **VueJS**, but it is not required to install the **VueJS CLI**. But it is recomended you have **NodeJS** already installed.

### Bootstrap JQuery
The **Bootstrap JQuery** framworks does not have any requirements that needs to be installed. Once you have installed <a href="https://laragon.org/download/" target="_blank">Laragon</a>, <a href="https://www.apachefriends.org/download.html" target="_blank">XAMPP</a> or any orther dev server, you are ready to create Bootstrap and JQuery projects.

## Publish Platforms
### Desktop Platform with Quasar💻
The requirement for developing a Desktop app with Quasar, is <a href="https://quasar.dev/quasar-cli-webpack/developing-electron-apps/introduction" target="_blank">Electron</a>. When you click on the Desktop platform during publish, **Radsystems Studio** runs the <a href="https://quasar.dev/quasar-cli-webpack/developing-electron-apps/preparation" target="_blank">`quasar mode add electron`</a> command, which downloads and adds the necessary files to your project. You can find the configurations available for Quasar Desktop to use in quasar.config.js file <a href="https://quasar.dev/quasar-cli-webpack/developing-electron-apps/configuring-electron" target="_blank">here</a>.

### Mobile Platform with Quasar📱
In order to develop mobile app with Radsystems Studio, there are multiple requirements that need to be installed properly for it to work.
- Visit [Quasar mobile development requirement docs](https://quasar.dev/quasar-cli/developing-cordova-apps/preparation#-add-cordova-quasar-mode)

# Others
> You can use <a href="https://laragon.org/download/">Laragon</a>  or <a href="https://www.apachefriends.org/download.html">XAMPP</a>. It has already PHP, MySQL/MariaDB and PhpMyAdmin to manage databases.
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
