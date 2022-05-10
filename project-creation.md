---
title: Project Creation
description: Creating a new Project is very easy with Radsystems ...
published: true
date: 2022-05-10T23:45:30.163Z
tags: new project, creating a new project
editor: markdown
dateCreated: 2021-06-30T04:48:13.567Z
---

# Creating a New Project

> **Note:** Before you create a project in Radsystems Studio, please make sure you have created your database witht the database server of your choice.
{.is-warning}

## Project types {.tabset}

### PHP - Laravel <i class="mdi mdi-laravel"></i> + Vue Quasar <i class="mdi mdi-vuejs"></i>
![phpradvue-php-laravel-vue-quasar.png](/getting-started/phpradvue-php-laravel-vue-quasar.png)

### PHP - Laravel <i class="mdi mdi-laravel"></i> + PrimeVue <i class="mdi mdi-vuejs"></i>
![phpradvue-php-laravel-primevue.png](/getting-started/phpradvue-php-laravel-primevue.png)

### PHP - Laravel <i class="mdi mdi-laravel"></i> + Bootstrap & JQuery <i class="mdi mdi-bootstrap"></i>
![phpradclassic-php-laravel-bootstrap-jquery.png](/getting-started/phpradclassic-php-laravel-bootstrap-jquery.png)

### NodeJS - Express <i class="mdi mdi-nodejs"></i> + Vue Quasar <i class="mdi mdi-vuejs"></i>
![noderadvue-nodejs-express-vue-quasar.png](/getting-started/noderadvue-nodejs-express-vue-quasar.png)

### NodeJS - Express <i class="mdi mdi-nodejs"></i> + PrimeVue <i class="mdi mdi-vuejs"></i>
![noderadvue-nodejs-express-primevue.png](/getting-started/noderadvue-nodejs-express-primevue.png)

### Python - Flask <i class="mdi mdi-language-python"></i> + Vue Quasar <i class="mdi mdi-vuejs"></i>
![pyradradvue-python-flask-vue-quasar.png](/getting-started/pyradradvue-python-flask-vue-quasar.png)

### Python - Flask <i class="mdi mdi-language-python"></i> + PrimeVue <i class="mdi mdi-vuejs"></i>
![pyradradvue-python-flask-primevue.png](/getting-started/pyradradvue-python-flask-primevue.png)

### ASP .Net Core <i class="mdi mdi-dot-net"></i> + Vue Quasar <i class="mdi mdi-vuejs"></i>
![aspradvue-asp-.net-core-vue-quasar.png](/getting-started/aspradvue-asp-.net-core-vue-quasar.png)

### ASP .Net Core <i class="mdi mdi-dot-net"></i> + PrimeVue <i class="mdi mdi-vuejs"></i>
![aspradvue-asp-.net-core-primevue.png](/getting-started/aspradvue-asp-.net-core-primevue.png)


# Enter project details

![create-new-project-panel.png](/getting-started/create-new-project-panel.png)

1. Enter your project name, it should only contain any of the following alphabets, numbers, and spaces. You should avoid special characters in order not to get errors while publishing your project.
2. Project location is automatically set, but you can change it to a different folder.
> **Note:** If you want to set the default location you want to use for new projects, you will have to do it from <kbd>Global Settings</kbd> <kbd>></kbd> <kbd>ProjectsDefaultDirectory</kbd>, by selecting a new folder.
{.is-info}
3. Site Address is set to the default, but your project is running on a different port order than the one set, you can add the correct site address.
4. You can select the default language you want to use for you project, and also turn on myultiple language support. The list of languages supported are: `English, French, Russian, Chinese, Italian, Hindi, Portuguese, German, Spanish, and Arabic`.
> Becareful with this, as you cannot change it later on in the project. In order to change the default language, you will have to recreate the project.
{.is-warning}
5. Next, you select your project icon. depending on the project type, there are different icons availble.
### Icon types {.tabset}
#### Vue Quasar <i class="mdi mdi-vuejs"></i>
##### Icons
- Material-Icons
- FontAwesome-v5
- Line-Awesome

#### PrimeVue <i class="mdi mdi-vuejs"></i>
##### Icons
- PrimeIcons

#### Bootstrap & JQuery <i class="mdi mdi-bootstrap"></i>
##### Icons
- Material-Icons
- Simple-Line-Icons
- FontAwesome
- Drip-Icons

# Select Database

## Database types {.tabset}

### MariaDB/MySQL

### SQLite

### Postgres

### MSSQL

##
> Please note that if you do not understand these settings, it is better to leave them to the default values set by **Radsystems Studio**. 
{.is-warning}






















![project-creation-1.jpg](/pages/project-creation/project-creation-1.jpg)

Select a type of project that you want to develop*.

These might be:

- Generate Classic Web aplication With (JQuery, Bootstrap-4)

> **PHPRad Classic** - *Generate Classic App with PHP Laravel, Bootstrap-4, JQuery*



- or Generate SPA, PWA, Desktop Apps and Mobile Apps With (VueJS, Quasar Framework)

> **PHPRad Vue** - *Generate SPA, PWA, Desktop Apps and Mobile Apps With PHP Laravel, VueJs Quasar Framework*

> **PyRad Vue** - *Generate SPA, PWA, Desktop Apps and Mobile Apps With Python Flask, VueJs Quasar Framework*

> **NodeRad Vue** - *Generate SPA, PWA, Desktop Apps and Mobile Apps With Node ExpressJS, VueJs Quasar Framework*

> **ASPRad Vue** - *Generate SPA, PWA, Desktop Apps and Mobile Apps With ASP.Net Core, VueJs Quasar Framework*

*in this case we choise a PHPRad Classic Project with a MySQL database connection.


---

## STEP 2 - Setting Project Information

![project-creation-2.jpg](/pages/project-creation/project-creation-2.jpg)

- 1 - Project Name: Set the name of your Project.
- 2 - Project Location: Set the Location of your Project.
- 3 - Site Address: The URL where you can test your project in a web browser.
- 4 - Default Language: Set the language for your project. You can choose between several languages.
![project-creation-2-c.jpg](/pages/project-creation/project-creation-2-c.jpg)

- 5 - Project Icon: Set the Icon's Group for your project. You can choose between several Icon's Group.


![project-creation-2-b.jpg](/pages/project-creation/project-creation-2-b.jpg)


---

## STEP 3 - Setting the Data Base Connections

![project-creation-3.jpg](/pages/project-creation/project-creation-3.jpg)

- 1 - Select Database: Select the database engine you want to use for your project.
- 2 - Server and Port: Set the Server and Port of your database connection.
- 3 - User: Set the user for your database engine.
- 4 - Password: The password for your user
- 5 - Database: Select the database for your project. 
- 6 - Or you can create a new.
![project-creation-2-d.jpg](/pages/project-creation/project-creation-2-d.jpg)

- 7 - Finally Click on "Create Project"

If everything went well, you may see a screen like the following:

![project-creation-2-e.jpg](/pages/project-creation/project-creation-2-e.jpg)

Nice work!

# PHPRad Classic
We will build a new web application using PHPRad Classic from scratch.

1. In the RadSystems Studio, Click **New Project** next to PHPRad Classic.
![1.png](/phprad-classic/1.png)

2. In the next window, we will specify the following: (*Note: You can use whatever value you want*)
- Project Name: *Classic 4 First* 
- Project Location: *Leave it as default*
- Site Address: Leave *it as default*
- Language: English (You can check multi-language if you want.)
- Project Icon: FontAwesome
- Database: MariaDB
- Database Server: localhost
- Database Port: 3306 
- Database User: root
- Database Password: yourdbpassword
![2.png](/phprad-classic/2.png)

3. Click **Create New Database** button. A small window appear where we can specify our new Database Name to be created.
![3.png](/phprad-classic/3.png)

4. Click **Create Database**, then a popup window appear informing you that the new database has been created. Click **OK** to continue.
![4.png](/phprad-classic/4.png)

5. Now, click **Create Project** button.
![5.png](/phprad-classic/5.png)

6. You will now then prompted with the **Manage Project Database** window where we can create DB Tables and Fields. Click **OK** to continue.
![6.png](/phprad-classic/6.png)

7. In this example, we will be creating 1 table only called **Orders** with the fields of:
- id (Int, Auto Increment, Primary Key)
- order_no (varchar, size=15, NOT NULL)
- date (date, NOT NULL)
- remarks (text, NULL)
![7.png](/phprad-classic/7.png)

8. Click **Save Changes**. You can now see the main window where you modify your applications settings and attributes.
![8.png](/phprad-classic/8.png)

9. Click **Publish** button.
![9.png](/phprad-classic/9.png)
![10.png](/phprad-classic/10.png)

10. Once the publish is done, you will see the command prompt window stating the the application is ready. Take note of link presented in the command prompt like *http://localhost:8050*
![11.png](/phprad-classic/11.png)

11. Now goto to your favorite browser and the link *http://localhost:8050*

12. **Congratulation!!!** You have now the complete CRUD application using PHP Laravel, Bootstrap 4 and JQuery. Thanks to RadSystems Studio.
![12.png](/phprad-classic/12.png)
![13.png](/phprad-classic/13.png)
![14.png](/phprad-classic/14.png)


# PHPRad Vue


# NodeRad Vue
We will build a new web application using NodeRad Vue from scratch.

1. In the RadSystems Studio, Click **New Project** next to NodeRad Vue.
![1.png](/noderad-vue/1.png)

2. In the next window, we will specify the following: (*Note: You can use whatever value you want*)
- Project Name: *First Node Vue* 
- Project Location: *Leave it as default*
- Site Address: Leave *it as default*
- Language: English (You can check multi-language if you want.)
- Project Icon: Line-Awesome
- Database: MariaDB
- Database Server: localhost
- Database Port: 3306 
- Database User: root
- Database Password: yourdbpassword
![2.png](/noderad-vue/2.png)

3. Click **Create New Database** button. A small window appear where we can specify our new Database Name to be created.
![3.png](/noderad-vue/3.png)

4. Click **Create Database**, then a popup window appear informing you that the new database has been created. Click **OK** to continue.
![4.png](/noderad-vue/4.png)

5. Now, click **Create Project** button.
![5.png](/noderad-vue/5.png)

6. You will now then prompted with the **Manage Project Database** window where we can create DB Tables and Fields. Click **OK** to continue.
![6.png](/noderad-vue/6.png)

7. In this example, we will be creating 1 table only called **Orders** with the fields of:
- id (Int, Auto Increment, Primary Key)
- order_no (varchar, size=15, NOT NULL)
- date (date, NOT NULL)
- remarks (text, NULL)
![7.png](/noderad-vue/7.png)

8. Click **Save Changes**. You can now see the main window where you modify your applications settings and attributes.
![8.png](/noderad-vue/8.png)

9. Click **Publish** button.
![9.png](/noderad-vue/9.png)
![10.png](/noderad-vue/10.png)

10. Once the publish is done, you will see the 2 command prompts window, 1 for the Backend API and the other 1 is the frontend.Take note of link presented in the command prompt like *http://localhost:8050*
![11.png](/noderad-vue/11.png)

11. Now go to your favorite browser and the link *http://localhost:8050*

12. **Congratulation!!!** You have now the complete CRUD application in NodeJS + Vue. Thanks to RadSystems Studio.
![12.png](/noderad-vue/12.png)
![13.png](/noderad-vue/13.png)
![14.png](/noderad-vue/14.png)



# PyRad Vue


# ASPRad Vue
