---
title: Authentication
description: Setup authentication to your application
published: true
date: 2025-01-07T00:50:39.728Z
tags: security, authentication, username, password
editor: markdown
dateCreated: 2021-07-25T22:01:01.212Z
---

# Authentication
**RadSystems Studio** has a built-in component for user authentication process, with this you can implement security for your app in just a couple of minutes.

## Prerequisite
- Database table to store user's credentials.
- The table should have the following fields:
	- id
  - username
  - password
  - email
  - photo *(Optional, String type)*
 
## Create User Table
1. In RadSystems Studio main interface, click **Manage Database Tables** icon.
![1.png](/security/1.png)

2. In the Manage Database Window, Click **Add Table**.
![2.png](/security/2.png)

3. Set the following data to the newly created table: (*Note: you can put any value you like*).
	- **Table Name:** users
	- **Fields:** id (INT AUTO INCREMENT PRIMARY)
	- **Fields:** username (VARCHAR, size: 50)
	- **Fields:** password (VARCHAR, size: 255)
	- **Fields:** email (VARCHAR, size: 100)
	- **Fields:** photo (VARCHAR, size: 255, NULL)
![3.png](/security/3.png) 

4. Click **Save Changes** button

## Setup
1. In **RadSystems Studio** main interface, click **Authentication** from the menu bar.
![4.png](/security/4.png)
![5.png](/security/5.png)

2. A **Login and Registration Setup** appear, plot the User Table & Fields we created above:
	- **Registration Table:** User (*This is the table we created* )
	- **User Name Field:** username
	- **Password Field:** password
	- **User ID Field:** id
	- **Email Field:** email
	- **Photo Field:** photo

3. You can Enable/Disable the **Remember Me** functionality.
4. **Login Mode:**
	- Username Or Email
	- Email Only
	- Username Only
5. **Allow users to register:** This will add a registration module to your application
6. **Force Email Verification:** If set, your application will send an activation link through the registered email before they can use their account.
7. **Auto Login After Registration:** This will redirect to the main page after the registration. (*Note: you must disable the Force Email Verification Option for this to work*)
8. **Enable Password Reset:** As the name suggested, it allows the user the ability to click the forgot password option.
9. On the right side of the window, You can specify by checking the specific page that you want to exclude from authentication. By default, all pages will be authenticated.
10. If you are done, click **Okay** button
11. In the main window of **RadSystems Studio**, click **Publish**.
12. **Congratulations!!!** User authentication has been added to your application.
![6.png](/security/6.png)


