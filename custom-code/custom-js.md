---
title: Custom Javascript Code
description: Modify or Create custom VueJS code
published: true
date: 2021-07-30T01:03:46.578Z
tags: custom, vuejs, javascript, code
editor: markdown
dateCreated: 2021-07-30T01:01:05.434Z
---

# Custom Javascript Code
Writing Custom Javascript Code in our application.

## NodeRad Vue
Knowledge in VueJS is a must, you can check the VueJS documentation here https://vuejs.org/v2/guide/

   - Setup
		1. Select the Table (e.g **Order** table)
		2. Select which Page (e.g **List Page**)
		3. Tick the **Edit Code** checkbox
		4. Goto **Edit Page Js** Tab


In this example we will write an alert message everytime the page is loaded.

`created: function(){
	alert("Hello World");	
}`

![1.png](/custom-code/noderad/1.png)

When we publish the application, you can see the pop-up message "hello world" everytime the Order List Page is loaded.
![2.png](/custom-code/noderad/2.png)