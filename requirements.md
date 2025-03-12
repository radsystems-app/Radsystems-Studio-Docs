---
title: System Requirement
description: 
published: true
date: 2025-03-12T12:30:52.507Z
tags: 
editor: markdown
dateCreated: 2021-08-03T03:09:09.844Z
---

> **System requirements** will vary on what application you want to create.
{.is-info}

# Operating System
**Radsystems Studio** currently supports only the **Windows Operating System(OS)**, **Windows x86/x64 (7, 8, 10, 11)**. You can download the OS from the <a href="https://www.microsoft.com/en-us/software-download/" target="_blank">Microsoft Website</a>. For those using other operating systems, you will need to install a **Virtual Machine (VM)** and then install the supported windows OS to that **Virtual Machine (VM)** in order to install **Radsystems Studio** in it.
- <a href="https://www.virtualbox.org/wiki/Downloads" target="_blank">VirtualBox (MacOS, Linux, Solaris)</a>
- <a href="https://wiki.winehq.org/Download" target="_blank">Wine (Linux, MacOS, Android)</a>
- <a href="https://www.parallels.com/" target="_blank">Parallels Desktop (MacOS)</a>
- <a href="https://www.vmware.com/products/fusion.html" target="_blank">VMWare (MacOS, Linux)</a>
- <a href="https://www.codeweavers.com/crossover/" target="_blank">CrossOver (ChromeOS, MacOS, Linux)</a>

These are just a few options out there.
# Development Servers
The recommended development server for Radsystems Studio is <a href="https://github.com/leokhoa/laragon/releases/tag/6.0.0/" target="_blank">Laragon</a>. <a href="https://github.com/leokhoa/laragon/releases/tag/6.0.0/" target="_blank">Laragon</a> gives the option to install multiple versions of <a href="https://www.php.net/" target="_blank">PHP</a>, <a href="https://nodejs.org/en/" target="_blank">NodeJS</a>, <a href="https://www.python.org/downloads/" target="_blank">Python</a>, etc.

## Database
**Radsystems Studio** currently supports 5 database types, (<a href="https://mariadb.org/download/" target="_blank">MariaDB</a> or <a href="https://dev.mysql.com/downloads/installer/" target="_blank">MySQL</a>), <a href="https://www.sqlite.org/download.html" target="_blank">SQLite</a>, <a href="https://www.postgresql.org/download/" target="_blank">PostgreSQL</a>, <a href="https://www.microsoft.com/en-us/sql-server/sql-server-downloads" target="_blank">MSSQL Server</a>, and <a href="https://www.microsoft.com/en-us/sql-server/sql-server-downloads" target="_blank">ORACLE (only supported with Node.TS project types)</a>.

## Backend Framework (API)
Backend Frameworks are the aspect of the project that runs and is executed on the server.

### PHP - Laravel
The **PHP -  Laravel** depends on **Laravel 11.30** framework, which requires **PHP >= 8.2** and Composer for package management. But if you download and install the <a href="https://github.com/leokhoa/laragon/releases/tag/6.0.0/" target="_blank">Laragon</a> full setup, you are ready to develop a **Laravel, Boostrap & jquery(PHPRad Classic)** project.

If you choose to install just php and composer, then you can download them from the links below:
- <a href="https://laravel.com/docs/11.x" target="_blank">Laravel 11.30</a>
- <a href="https://www.php.net/downloads.php" target="_blank">PHP >= 8.2</a>
- <a href="https://getcomposer.org/download/" target="_blank">Composer</a>

### NodeJS - Express
The **NodeJS - Express** framework depends on **NodeJS version 20** and above, but it is recomended you use **NodeJS version 20** or any of the **<a href="https://nodejs.org/en/" target="_blank">Long Term Support(LTS)</a>** versions. Once it is installed, you are ready to use the **NodeJS - Express** and **NodeTS - Express** backend framework.

> Please note that, It is recomended you download any of the **<a href="https://nodejs.org/en/" target="_blank">Long Term Support(LTS)</a>** versions.
{.is-info}

### Python - Flask
The **Python - Flask** framework depends on e **<a href="https://www.python.org/downloads/" target="_blank">Python >= 3.9</a>** Once it is installed, you are ready to use the **Python - Flask** backend framework.

### ASP .Net Core
The **ASP .Net Core** framework depends on **<a href="https://dotnet.microsoft.com/en-us/download/dotnet/3.1" target="_blank">.NET Core 3.1</a>** or any of the **LTS** versions. Once it is installed, you are ready to use the **ASP .Net Core** backend framework.

## Frontend Framework (UI)
These are the frameworks used for generating the HTML, CSS and JavaScript for the projects.

### Vue Quasar
The **Vue Quasar** framework depends on **NodeJS version 20**, **Quasar CLI**. It is recomended you use **NodeJS version 20**. After installing **NodeJS**, you can install **Vue Quasar CLI** using `npm i -g @quasar/cli`, if you don't and you try to create a project, **Radsystems Studio** will prompt you to intsall it.

### PrimeVue
The **PrimeVue** framework depends on **VueJS**, but it is not required to install the **VueJS CLI**. But it is recomended you have **NodeJS** already installed.

### Bootstrap JQuery
The **Bootstrap JQuery** frameworks does not have any requirements that needs to be installed. Once you have installed <a href="https://github.com/leokhoa/laragon/releases/tag/6.0.0/" target="_blank">Laragon</a>, <a href="https://www.apachefriends.org/download.html" target="_blank">XAMPP</a> or any orther dev server, you are ready to create Bootstrap and JQuery projects.

## Publish Platforms
### Desktop Platform with Quasar💻
The requirement for developing a Desktop app with Quasar, is <a href="https://quasar.dev/quasar-cli-webpack/developing-electron-apps/introduction" target="_blank">Electron</a>. When you click on the Desktop platform during publish, **Radsystems Studio** runs the <a href="https://quasar.dev/quasar-cli-webpack/developing-electron-apps/preparation" target="_blank">`quasar mode add electron`</a> command, which downloads and adds the necessary files to your project. You can find the configurations available for Quasar Desktop to use in quasar.config.js file <a href="https://quasar.dev/quasar-cli-webpack/developing-electron-apps/configuring-electron" target="_blank">here</a>.

### Mobile Platform with Quasar📱
In order to develop mobile app with **Radsystems Studio**, there are multiple <a href="https://quasar.dev/quasar-cli-vite/developing-cordova-apps/preparation#-start-developing" target="_blank">requirements</a> that needs to be met before you can do so.

- You need to download and install <a href="https://developer.android.com/studio" target="_blank">Android Studio</a>.
- After installing <a href="https://developer.android.com/studio" target="_blank">Android Studio</a>, you need to add your android SDK path to `ANDROID_HOME` and `ANDROID_SDK_ROOT`.
![add-android-sdk-root.png](/getting-started/add-android-sdk-root.png)
- Download and install <a href="https://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html" target="_blank">JDK</a>
- Add JDK installation path to `JAVA_HOME`, similar to what was done for `ANDROID_HOME` and `ANDROID_SDK_ROOT`, and then add JDK bin(`C:\Program Files\Java\jdk1.8.x\bin`) and JRE(`C:\Program Files\Java\jre1.8.x`) to path variable. 
> Please use the path where your JDK was installed, the paths above are just examples.
{.is-warning}

- Download, install and add <a href="https://downloads.gradle-dn.com/distributions/gradle-4.10.3-all.zip" target="_blank">Gradle</a> to environmental variable.
You can read more from <a href="https://quasar.dev/quasar-cli-vite/developing-cordova-apps/preparation#-start-developing" target="_blank">Quasar mobile development requirement docs</a>

# Setup Environment Variables
Some installations need to manually encode their parent folder in Windows Environment variables (e.g **PHP**, **Android**, **Java**, **python** and **pip**). 

To loacate the **Environmental Variables** panel, click on **Sart Menu**, click on **Control Panel**, click on **Systems**, click on **Advance system settings**, then click on **Environment Variables**.
E.g <kbd>Sart</kbd> <kbd>></kbd> <kbd>Control Panel</kbd> <kbd>></kbd> <kbd>Systems</kbd> <kbd>></kbd> <kbd>Advance system settings</kbd> <kbd>></kbd> <kbd>Environment Variables</kbd>

![environmental-variables.png](/getting-started/environmental-variables.png)

To add an app to the path variable, click on **Path** variable from either **User variables** or **System Variables** section, click on **Edit**, then click on **New** and add the application path to it.
E.g <kbd>Path</kbd> <kbd>></kbd> <kbd>Edit</kbd> <kbd>></kbd> <kbd>New</kbd>

![add-app-to-path.png](/getting-started/add-app-to-path.png)

Below are the list of paths you need to enter if they dont already exist:
- Add **XAMPP PHP** Path `C:\xampp\php` or else locate you **PHP** installation path and add it.
- Add **Python** path `%localappdata%\Programs\Python\Python39` (*This is the path of my python.exe*).
- Add **Python Script** path `%localappdata%\Programs\Python\Python39\Scripts` (*This is the path of my pip.exe*).
- Add **.NetCore** path `%programfiles%\dotnet` (*This is the path of my dotnet.ext*).

> When done, click on the **Okay** button to save it, then restart your computer if needed.
{.is-success}

