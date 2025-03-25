---
title: Release Notes
description: Radsystems Studio release notes
published: true
date: 2025-03-25T20:00:04.855Z
tags: releases, change logs
editor: markdown
dateCreated: 2021-12-03T16:13:58.048Z
---

# *Version 9.0.0* - (24-03-2025)
### *New Features* 🚀
- **Template Version Display**: Added the ability to display the template version for better clarity.
- **Trial Activation**: Users can now activate the app when the trial ends instead of being forced to close it.
- **Clickable License Notification**: Made the "**License has ended**" message clickable for easier activation.

### *Improvements* ✨
- **Component Naming**: Improved naming conventions for "Row" and "Column" components in the Radsystems IDE.
- **Project Creation**: Simplified project creation by clearly displaying supported frameworks.
- **Theming Configuration**: Redesigned the theming configuration for PrimeVue for a more intuitive experience.

### *Removals/Deprecations* 🗑
- **Backward Compatibility**: Projects created using previous versions like version 8, are not forward-compatible with version 9, and vise vasa.
- **Top-Left Menu**: Deprecated the **Top-Left** menu across all frontend frameworks. There only two menu positions, top right and side menu.
- **Global Settings**: Removed global settings to streamline the interface.
- **Calendar Component**: Removed the calendar component from page design.
- **Push to git**: Removed push to git from the window.

### *New Page Events* 🛠
- Introduced **BeforeListExport**, **BeforeViewExport**, **BeforeImport**, and **AfterImport** events in **PageEvents** for enhanced customization.

### *Bug Fixes* 🐞
- Resolved and issue with **Roles & Permissions** and **Audits Trail** configuration on **ASP.Net Core** project type.

## :hash: *Components v2.0.0* - (24-03-2025)

### *Upgrades* 🔄
- **ASP.Net Core**: Upgraded the target framework to **net9.0**.
- **Prime Vue**: Upgraded from version **3** to version **4**, and switched from **Webpack** to **Vite**.
- **Quasar Vue**: Switched from **Webpack** to **Vite**.
- **Prime React**: Switched from **Webpack** to **Vite**.

### *New Additions* 🌟
- **Tailwind CSS Support**: Added support for **Tailwind CSS** in **Prime Vue** and **Prime React**.

### *Bug Fixes* 🐞
- Resolved an issue where selecting a **non-PNG** app icon caused it to not appear in the generated app.


# Verion 8.x
## Version 8.7.4 - (15-11-2024)
- :bug: **Fixed** a bug with **Date String not recognized** when starting up **Radsystems Studio**.
- ### :hash: Components v1.0.10 - (02-02-2025)
	- :fire: **Added** to PHP Laravel + Bootstrap JQuery - The Footer menu items can now be easily changed from the **config/settings.php** file.
	- :fire: **Added** to PHP Laravel + Bootstrap JQuery - Texts in other action messages now support translations. A separate section - "messages" - was added to the "validation" language file.
	- :bug: **Fixed** PHP Laravel + Bootstrap JQuery - Page Custom Validation. The error was not showing up and the page always redirected to a blank form. 
	- :bug: **Fixed** PHP Laravel + Bootstrap JQuery - Form values were not retained upon redirect after error. 
	- :bug: **Fixed** PHP Laravel + Bootstrap JQuery - Issue of "**Custom action button's link not working**" resolved.
	- :white_check_mark: **Improved** **BeforeAdd**, **BeforeUpdate**, **BeforeDelete** in PageEvent, it now supports "**cancel process**" with "**custom error message**".
	- :white_check_mark: **Improved** Bootstrap JQuery - The design for error and success message alerts.
	- :white_check_mark: **Improved** PHP Laravel + Bootstrap JQuery - URL Sanitization added for dynamic link building. 
	- :white_check_mark: **Improved** PHP Laravel + Bootstrap JQuery - The copyright line in the application footer can now be changed from the **config/settings.php**.
	- :x: **Removed Qcalendar** app extension from **package.json** temporarily for **Quasar** projects.
- ### :hash: Components v1.0.9 - (13-12-2024)
	- :fire: A new configuration file located at **app/config/settings.php** has been introduced to enable advanced customization of your **Laravel + Bootstrap & jQuery** application without modifying core application files.
	- :fire: You can now configure customized brand information for reports **(Print and PDF)** directly in the settings.php file for **Laravel + Bootstrap & jQuery** projects.
	- :fire: An option has been added to enable or disable the header section in the report blade templates **(Print and PDF)** via the **config/settings.php** file for **Laravel + Bootstrap & jQuery** projects.
	- :fire: An option has been added to enable or disable the footer section in the report blade templates **(Print and PDF)** via the **config/settings.php** file for **Laravel + Bootstrap & jQuery** projects.
	- :fire: The ability to change the font style and font size for reports **(Print and PDF)** is now available through the **config/settings.php** file for **Laravel + Bootstrap & jQuery** projects.
	- :fire: You can now customize the footer copyright text for reports **(Print and PDF)** directly in the **config/settings.php** file for **Laravel + Bootstrap & jQuery** projects.
	- :fire: A dynamic token, **{YEAR}** in **config/settings.php**, has been added for use in the footer copyright of reports **(Print and PDF)** for **Laravel + Bootstrap & jQuery** projects. This token will automatically update to the current year.
 	- :bug: **Fixed** a bug in **Python Flask** projects were no data is loaded for a select field, when it is configured.
	- :bug: **Fixed** an issue where the requirement.txt file is replaced with another file and causes errors in **Python Flask** projects.
	- :bug: **Fixed** a bug with file upload in **Python Flask** projects.
	- :bug: **Fixed** vulnerability in **ASP.Net Core** Projects, by updating its dependencies.
	- :bug: **Fixed** "Class not found" error during image upload for **Laravel + Bootstrap & jQuery** projects.
	- :bug: **Addressed** an issue in the image library that caused errors when resizing images post-upload for **Laravel + Bootstrap & jQuery** projects.
	- :bug: **Corrected** footer menu alignment by updating incorrect Bootstrap 5 classes for the footer element for **Laravel + Bootstrap & jQuery** projects.
	- :bug: **Replaced** the hard-coded year value in the footer with a dynamic year value for **Laravel + Bootstrap & jQuery** projects.
	- :bug: **Fixed** an issue where the uploaded image failed to process correctly for projects with **Laravel Backend**.
	- :bug: **Resolved** a bug where the image path was not being saved to the database when resizing options were applied for projects with **Laravel Backend**.
	- :white_check_mark: **Changed** the hard-coded date in the application's footer to a dynamic date that updates automatically for projects using **primeVue Frontend**.
- ### :hash: Components v1.0.8 - (15-11-2024)
	- :sparkles: **Upgraded Express TS** and its dependencies to the latest version (4.21.1).
	- :sparkles: **Upgraded Express JS** and its dependencies to the latest version (4.21.1).
	- :sparkles: **Upgraded Quasar** app dependencies.
	- :sparkles: **Upgraded Python Flask** and its project dependencies, **Python >=3.9** is the new required version.
	- :sparkles: **Upgraded Bootstrap** frontend and its themes to **version 5.3.3**.
	- :sparkles: **Upgraded Laravel** to **v11.30** and all dependencies used.
	- :sparkles: **Upgraded** Captcha plugin for **Laravel + Bootstrap**.
	- :sparkles: **Upgraded VueCharts.vue** component: changed Chart import to 'chart.js/auto' for **PrimeVue** frontend.
	- :sparkles: **Upgraded PrimeVue** dependencies to the latest, preparing it for a **major upgrade** in future releases.
	- :bug: **Fixed** a bug with **Laravel** email verification, when verifying email is configured for **Laravel** and any of the **Vue.JS frontend**.
	- :bug: **Fixed** an issue with **Python Flask**, where *"AttributeError: 'tuple' object has no attribute"* is encountered when adding or editing records on some **Python** versions.
	- :bug: **Fixed** a bug with **Firebase\JWT\ library** for **Laravel** backend.
	- :bug: **Fixed** page redirect issue when **OTP** is configured and then the app is hosted in a sub-folder in production for **Vue projects**.
## Version 8.7.3 - (31-10-2024)
- :white_check_mark: **Improved** Template system. **Radsystems Studio** subscribers will now receive fast updates for **Template** separately from application updates.
- ### :hash: Components v1.0.7 - (31-10-2024)
	- :sparkles: **Upgraded** Pillow library to support **Python 3.13.0** for **Python Flask projects**.
	- :bug: **Fixed** a bug with **AutoFill** in **Node.js + PrimeVue** project type.
	- :bug: **Fixed** issue on **Laravel + Bootstrap** project **List Pages**, where the dropdown menu for **View**, **Edit**, and **Delete** is hidden behind the **List Page**.
## Version 8.7.0 - (24-04-2024)
- :bug: **Fixed** a minor bug with PrimeVue frontend.
## Version 8.6.9 - (22-04-2024)
- :bug: **Fixed** MSSQL bug where reading the database throws a schema error.
- :bug: **Fixed** Laravel + Bootstrap bug where duplicating a list or view page containing a master details configuration, causes an error.
- :bug: **Fixed** Laravel + Bootstrap bug where setting UseCustomSelect throws an error.
- :bug: **Fixed** Node Express JS where PDFs are not generated when the app is hosted on a Linux server.
- :bug: **Fixed** Node Express JS + PrimeVue bug where, when you set a View or List page field to use Html5Video an error is encountered.
- :bug: **Fixed** Node Express JS + PrimeVue bug where AppendIcon when configured is not found.
- :bug: **Fixed** Node Express JS + PrimeVue bug where page exclusion from auth does not work, and when a page is created from Page Designs and deleted, it remains in the frontend custom folder.
- :bug: **Fixed** Vue Quasar bug where the error is encountered when tabs, accordion, or modal components are added to a page when the project is published.
- :white_check_mark: Minor improvements.
- :white_check_mark: **Backward** compatible with version 8.5.9.
## Version 8.5.9 - (21-10-2023)
- :sparkles: **Upgraded** the Laravel framework used for projects to version 10, which supports PHP 8.1 and above.
- :sparkles: **Upgraded** Node.js project type to use ES6 and run on the latest Node.js version 18 LTS.
- :fire: **Added** Support for MySQL version 8.
- :fire: **Added** Support for Postgres Private Schemas.
- :fire: **Added** support for .NetCore version 6 LTS.
- :bug: **Fixed** Noderad + primevue bug that occur, when timestamp is configured for a table.
- :bug: **Fixed** Laravel + Bootstrap bug, where the captcha throws an error on the edit page. 
- :white_check_mark: Minor improvements.
- :x: **No** backward compatibility.
## Version 8.2.3
- :bug: **Fixed** Node + primevue, quasar, primereact. Error loading image.
- :bug: **Fixed** Setup file installation - After installating the software. Splash screen was in static display when clicked. The image disppeares and Error saving messagebox is displayed.
- :bug: **Fixed** Laravel Quasar:  GridOnMobile true error.
- :bug: **Fixed** Python Flask Primevue, quasar, react error.
- :bug: **Fixed** Quasar Projects: Error when you set GridOnMobile to True.
- :bug: **Fixed** TypeScript + PrimeVue + Quasar + React: Error adding the authentication module, roles and permissions.
- :bug: **Fixed** Setup file installation - Splash screen in static display when clicked. Image disppeares and Error saving messagebox is displayed.
- :bug: **Fixed** Flask + primevue: Error downloading as PDF
- :bug: **Fixed** Node, typescript, python: don't generate the records counts in the components.
## Version 8.1.8
- :bug: **Fixed** a minor bug in postgre db connection when schema is selected.
## Verion 8.1.6
- :bug: **Fixed** a bug where role dashboard is not diplayed for a role when configured in **Laravel + Bootstrap**.
- :bug: **Fixed** a bug in **Laravel + Bootstrap**, where the endpoint link displayed to the user is not correct.
- :bug: **Fixed** a bug with the calendar component for **Laravel + Bootstrap** projects.
- :bug: **Fixed** a bug with **Laravel** projects, when a search is done on the user table.
- :bug: **Fixed** a bug in **Action Before Update** of **Page Events**, where the parameter parsed to the before edit function is incomplete.
- :bug: **Fixed** a bug where an error icon code is generated when **Audit trail** is configured.
- :bug: **Fixed** a bug with Quasar projects where the action buttons are not display properly when the table has enough space to contain them.
- :bug: **Fixed** a bug with export not displaying in **Node.js + Quasar**.
- :bug: **Fixed** a bug with value property being generated twice for a "Text" input, where TextboxType is set to Time.
- :bug: **Fixed** a bug with calendar on **Python + Quasar**.
- :bug: **Fixed** a bug with **Remember Me** checkbox not clickable on **Node + React** project type.
- :scissors: **Removed** the "Having" configuration from the  List Page Properties.
## Verion 8.1.0
- :sparkles: **Upgraded** Bootstrap from Bootstrap 4 to Bootstrap 5.
- :fire: **Added** the option of publishing/pushing your project to GitHub.
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