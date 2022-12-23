---
title: Release Notes
description: Radsystems Studio release notes
published: true
date: 2022-12-23T00:32:20.170Z
tags: releases, change logs
editor: markdown
dateCreated: 2021-12-03T16:13:58.048Z
---

# Verion 8.x
## Verion 8.1.0
- :sparkles: **Upgraded** Bootstrap from Bootstrap 4 to Bootstrap 5.
- :fire: **Added** a new frontend framework called Prime React.
- :fire: **Added** a new Backend framework called *Node TS - Express*, for users who prefer to use typescript in place of Javascript.
- :fire: **Added** AutoFillInput, for auto populating fields based on a selected record.
- :bug: **Fixed** the bug where Tag Attributes for Action buttons are not working.
- :bug: **Fixed** Drop-down Menu arrow over lapping with the hamburger menu in Laravel + Bootstrap.
- :bug: **Fixed** a bug where Field Type "Select" - Default Selected Value is not applied on Laravel Classic projects.
- :bug: **Fixed** a bug where Buttons in header of List page ignore PageDisplaySettings under Component Properties, and always open the page as Link if set to Modal or Inline.
- :bug: **Fixed** a bug where Title icon in Header component displays an error.
- :bug: **Fixed** a bug where Meta Information from Project Settings is not being added to the generated application.
- :bug: **Fixed** a bug where Disabled and ReadOnly properties for Date picker in Laravel Classic projects does not work.
- :bug: **Fixed** a bug where Inline edit in Laravel Classic projects does not work on View page.
- :bug: **Fixed** a bug where setting DisplayTemplate to TabularList in Laravel Classic projects does not work on View page.
- :hash: **Redesign** of generated view page for Laravel + Bootstraps projects.
- :hash: **Redesign** of Roles are Permission for Laravel + Bootstraps projects.

# Version - 7.x
## Version - 7.1.2
- :bug: **Fixed** a few minor bugs.
## Version - 7.1.0
- :sparkles: Upgraded vue **quasar** project from **vue2** to **vue3**.
- :fire: Added a new **frontend framework** called **PrimeVue**.
- :fire: Added **Undo** and **Redo** for **Radsystems Studio editor**.
- :fire: Added **code snippets** to **Radsystems Studio editor**, to show sample codes.
- :bug: **Fixed** the bug where **routes** are not generated for **Endpoint on laravel project type**.
- :bug: **Fixed** a bug that causes **Radsystems Studio** to throw an error during publish for **laravel project types** when **Request Type** is set to **ANY** in Endpoints.
- :bug: **Fixed** the bug where **Radsystems Studio classic** app throws an error if an image is not compulsory and also not uploaded during **user registration/add**.
- :bug: **Fixed** a bug with **view** and **edit** in a **modal** not working on classic projects.
- :hash: Redesigned the **Join Tables** configuration window.
- :hash: Redesigned the **Radsystems Studio project creation** page for easy and smooth project creation.

# Version - 5.x
## Version - 5.1.4
- :fire: Added **2FA(2Factor Authentication)** configuration.
- :fire: Added Tag Attribute for components.
- :fire: Added **Image** Component .
- :fire: Added **Vuex store** configuration for projects using the vue **Quasar Framework**.
- :bug: **Fixed** the issue of the **Pages**, **Page Design**, **Publish**, and **Project Explorer** hiding on low resolution PC.
- :bug: **Fixed** the issue with **modal** and **Tab** component by adding ***ComponentName*** configuration to uniquely identify them.
- :bug: **Fixed** a bug with **Audit Trail** not working properly in Nodejs.
- :bug: **Fixed** the bug with **Roles and Permission** Configuration.
- :hash: Replaced **Dragging and Dropping** of **SubPages** in **Form Wizard** with **Form Wizard FormPage** Component Properties.
- :hash: Redesigned the **Page Custom JS** in **Page Design** for projects using the vue **Quasar Framework**.

## Version - 5.0.0
- :fire: Addition of 4 new components. 
- :fire: Implementation of auth2.
- :fire: Implementation of admin approve account.
- :bug: **Fixed** logo update bug in **PHPrad Classic** project.
- :bug: Other minor bug fixes.
- :hash: Redesign of master detail relationship. 
- :hash: Redesign of calendar. 
- :hash: Redesign of s3 upload.
- :hash: Redesign of file upload and file management.
- :white_check_mark: General improvements