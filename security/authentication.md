---
title: Authentication
description: Setup authentication to your application
published: true
date: 2021-07-27T01:09:00.609Z
tags: security, authentication, username, password
editor: markdown
dateCreated: 2021-07-25T22:01:01.212Z
---

# Authentication
**RadSystems Studio** has a built-in component for user authentication process, with this you can implement security for your app in just a couple of minutes.

## Pre-requisite
- Database table to store user's credentials.
- The table should have the following fields:
	- id
  - username
  - password
  - email
  - photo *(Optional, String type)*
 
## Create User Table
1. In RadSystems Studio main interface, click **Manage Database Tables** icon.
2. In Manage Database Window, Click **Add Table**.
3. Set the following data to the newly created table: (*Note: you can put any value you like*).
	- **Table Name:** users
	- **Fields:** id (INT AUTO INCREMENT PRIMARY)
	- **Fields:** username (VARCHAR, size: 50)
	- **Fields:** password (VARCHAR, size: 255)
	- **Fields:** email (VARCHAR, size: 100)
	- **Fields:** photo (VARCHAR, size: 255, NULL)
4. Click **Save Changes** button

## Setting Up
1. In **RadSystems Studio** main interface, click **Authentication Tab**.
2. A **Login and Registration Setup** appear, plot the User Table & Fields we created above:
	- **Registration Table:** User (*This is the table we created* )
	- **User Name Field:** username
	- **Password Field:** password
	- **User ID Field:** id
	- **Email Field:** email
	- **Photo Field:** photo

3. You can Enable/Disbable the **Remember Me** functionality.
4. Login Mode:
	- Username Or Email
	- Email Only
  - Username Only



