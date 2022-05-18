---
title: Page Events
description: Handle Page Actions
published: true
date: 2022-05-18T00:42:02.789Z
tags: 
editor: markdown
dateCreated: 2022-05-13T12:49:16.192Z
---

# Page Events
**Page Events** where you can insert a code that will run before and after the main action function.

![page-events.png](/page-events/page-events.png)

# How to Use
1. Click **Page Events** in the RS Toolbar - it will pop up the Page Events window.

![1.png](/page-events/1.png)

2. Click and expand the Pages Tree and click **"Before..."** or **"After..."**.

![2.png](/page-events/2.png)

3. Click **Edit Page Event** button to enable the code window.

![3.png](/page-events/3.png)

4. Put your code inside the function given.
5. On the right side, there is a built-in code snippet that you can use just by double clicking it.

![4.png](/page-events/4.png)
![5.png](/page-events/5.png)

# Example
For our example we will be creating a Log System where we can track every changes in our Todo App data.

1. Create Database, name it: **todo-db**
2. Create the first table, name it: **Todos**
3. Create 2 fields for Todos table
- **id** *(INT AUTO_INCREMENT PRIMARY NOT NULL)*
- **todo** *(VARCHAR(255) NOT NULL)*

4. Create the second table, name it: **Logs**
5. Create 4 fields for Logs table
- **id** *(INT AUTO_INCREMENT PRIMARY NOT NULL)*
- **dt** *(TIMESTAMP DEFAULT CURRENT_TIMESTAMP)*
- **action** *(VARCHAR(15) NOT NULL)*
- **todo** *(VARCHAR(255) NOT NULL)*

6. In RS Studio, Click Page Events (refer to #How To Use section
## PHPRad Classic
Coming Soon!

## PHPRad Vue
Coming Soon!

## NodeRad Vue
Coming Soon!

## PyRad Vue
Coming Soon!

## ASPRad Vue
Coming Soon!