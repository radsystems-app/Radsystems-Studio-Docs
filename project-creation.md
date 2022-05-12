---
title: Project Creation
description: Creating a new Project is very easy with Radsystems ...
published: true
date: 2022-05-12T17:48:26.365Z
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
3. Site Address is set to default, but if your project is running on a different port order than the one set, you can add the correct site address.
4. You can select the default language you want to use for you project, and also turn on myultiple language support. The list of languages supported are: `English, French, Russian, Chinese, Italian, Hindi, Portuguese, German, Spanish, and Arabic`.
> Becareful with this, as you cannot change it later on in the project. In order to change the default language, you will have to recreate the project.
{.is-warning}
5. Next, you select your project icon. depending on the project type, there are different icons available.
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
Before getting to this point, you need to make sure you have prepared your database connection details for the database of your choice.

## Database types {.tabset}

### MariaDB/MySQL
![select-database-maria-db-mysql.png](/getting-started/select-database-maria-db-mysql.png)
6. Select the database you want to use. By default **MariaDB** is selected which is the same as **MySQL**.
7. Enter your database server address here. If your database is on the same PC you are using for development, you should set the address to `localhost` or `127.0.0.1`. But if your database is in a remote **PC**, you need to make sure that you have allowed remote connections to the database.
8. Set your port here or leave it empty if you are using the default **MySQL/MariaDB** port.
9. Enter the **username** for the database here.
10. Enter the **password** for the database user here.
11. After entering the correct **server address**, **port**, **username**, and **password**, when you click on this select field, you should see a list of databases for the detail you have entered. Then select the database you want to use for the project.

### SQLite
![select-database-sqlite.png](/getting-started/select-database-sqlite.png)
6. Select **SQLite**.
7. Enter the name you want to use for your new SQLite database.
8. If you alrady have an **SQLite** database already created, click on this button to select it from the location where it is on you **PC**.

### Postgres
![select-database-postgres.png](/getting-started/select-database-postgres.png)
6. Select **PostgresDB**.
7. Enter your database server address here. If your database is on the same PC you are using for development, you should set the address to `localhost` or `127.0.0.1`. But if your database is in a remote **PC**, you need to make sure that you have allowed remote connections to the database.
8. Set your port here or leave it to the default port set if you are using the default **PostgresDB** port.
9. Enter the **username** for the database here or leave it to `postgres` if you are using the default **Postgres** user.
10. Enter the **password** for the database user here.
11. After entering the correct **server address**, **port**, **username**, and **password**, when you click on this select field, you should see a list of databases for the detail you have entered. Then select the database you want to use for the project.
> In some cases, you might have to enter the name of the database instead of selecting it from the list.
{.is-info}

### MSSQL
![select-database-mssql.png](/getting-started/select-database-mssql.png)
6. Select **MSSQL**.
7. Enter your database server address here. If your database is on the same PC you are using for development, you should set the address to `localhost` or `127.0.0.1`. But if your database is in a remote **PC**, you need to make sure that you have allowed remote connections to the database.
8. Set your port here or leave it blank if you are using the default **MSSQL** port.
9. Click this checkbox if you want to use **Windows Authentication** to connect to your **MSSQL** database. If this is used, then you can skip step **10** and **11**.
10. Enter the **username** for the database here.
11. Enter the **password** for the database user here.
12. After entering the correct **server address**, **port**, **username**, and **password**, when you click on this select field, you should see a list of databases for the detail you have entered. Then select the database you want to use for the project.
> In some cases, you might have to enter the name of the database instead of selecting it from the list.
{.is-info}


##
> Please note that if you do not understand these settings, it is better to leave them to the default values set by **Radsystems Studio**. 
{.is-warning}

![create-project-button.png](/getting-started/create-project-button.png)

After setting up your database detials, you need to click on the **Create Project** button for **Radsystems Studio** to connect to your database and create the default project configuration for your project.


# Save & Publish your Project
