---
title: PHPRad Classic
description: Create web application using PHPRad Classic
published: true
date: 2021-07-24T14:51:16.928Z
tags: new project, creating a new project, phprad classic, classic
editor: markdown
dateCreated: 2021-07-24T14:51:16.928Z
---

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

12. **Congratulation!!!** You have have now the complete CRUD application using PHP Laravel, Bootstrap 4 and JQuery. Thanks to RadSystems Studio.
![12.png](/phprad-classic/12.png)
![13.png](/phprad-classic/13.png)
![14.png](/phprad-classic/14.png)
