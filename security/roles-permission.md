---
title: Roles and Permission
description: Setup roles and permission
published: true
date: 2021-07-28T03:26:27.383Z
tags: security, setup, roles, permission
editor: markdown
dateCreated: 2021-07-27T01:28:17.429Z
---

# Roles and Permissions
Aside from [User Authentication](/en/security/authentication) security features, **RadSystems Studio** has a Role Based security too, this will make your app more secure by controlling the access of the certain user to a specif page

## Database Changes
This feature will automatically create the following:
- Create 1 DB Table for the Roles
- Create 1 DB Table1 for the Permissions
- add new field name: user_role to Users Table

## Pre-requisite
- User Authentication must be setup first. [Click here](/en/security/authentication) 

# PHPRad Classic
# PHPRad Vue
# NodeRad Vue
Step by Step
1. Click **Roles and Permmissios** button.
![1.png](/security/rolespermission/1.png)

2. Tick **Dynamic Role Permission**.
![2.png](/security/rolespermission/2.png)

2. By Default, there are 2 **User Roles** already setup (*Administor, User*). You can modify or remove those if you want.
3. In this example, we will create new **User Roles** (I named it: *Developer*)
![4.png](/security/rolespermission/4.png)
![5.png](/security/rolespermission/5.png)

4. Once created, Click the *Developer* Role (It should be highlighted now).
5. In **Page Permission** you can see all the modules/pages of your apps has, Checked **Role Pages**, down below select modules that you want to have roles.
6. In the right side, you can see the **Permission and PageAction** List, select the appropriate page action you want the Developer role has for that page.
![6.png](/security/rolespermission/6.png)

8. **Manage Tables**: here you can specify the table name and fields to be created. (I recommend to just leave it as default).
![7.png](/security/rolespermission/7.png)

8. Click **Save Changes**.

Now, In your main window, in Database Tables section, you will see the new tables and fields created.
![8a.png](/security/rolespermission/8a.png)

# PyRad Vue
# ASPRad Vue

# Test it out
Try to publish and test your apps now:
- In this example we will register new user (User1)
- After the registration, login the User1 user.
- Goto to Users Side Menu, as you can see the User1 "user role" is 1 by default. (1-Administrator, 2-User, 3-Developer)
- Click "Add New Users", and name it User2 with User Role = 2
- Once created, logout then login to User2 account.

As you can see on the Side Menu, some are not visible since User2 role is user.