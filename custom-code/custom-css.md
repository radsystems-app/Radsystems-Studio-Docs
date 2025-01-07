---
title: Custom CSS Code
description: Modify or Create custom CSS code
published: true
date: 2025-01-07T00:51:11.321Z
tags: 
editor: markdown
dateCreated: 2021-07-30T01:55:51.468Z
---

# Custom CSS
Modify or Create custom CSS Code.

In this example we will try to change the background color of the edit button.
![1.png](/custom-code/css/1.png)

## Setup
1. Select Table (e.g **Order** table)
2. Select which Page (e.g **List Page**)
3. Tick the **Edit Code** checkbox
4. Goto **Edit Page Css**
5. Enter this code below:

`.q-mx-xs{
   background-color:red !important;
 }`

> **q-mx-xs** is the class name of the edit button, you can verify that by going to **Edit Page View** tab.
{.is-info}

![3.png](/custom-code/css/3.png)

The output of our code would be like this:
![2.png](/custom-code/css/2.png)
