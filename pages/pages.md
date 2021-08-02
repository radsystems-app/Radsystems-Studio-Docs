---
title: Pages
description: Learn how to create and manage pages in RadSystems Studio
published: true
date: 2021-08-02T14:08:39.687Z
tags: 
editor: markdown
dateCreated: 2021-07-29T17:08:12.536Z
---

# Pages
RadSystem Studio pages are the core of application development. The pages panel is divided into four sections:
* Database Tables
* Table Pages
* Table Page Fields
* Table Page Properties
## Database Tables Section
![data-tables-section.png](/pages/data-tables-section.png){.align-center}
1. According to the graph, on the left side of the panel you can find the direct access to the tree database tables, in addition to the views created. You can create your own views too.
2. There is a three button menu. the first one allows you to change the details of the connection to the database.
3. The next button allows you to manage the Database. Through the interface, you can add, duplicate or delete tables and, for each table, you can manage the fields as well as the field type, size and other properties.
4. The last button synchronizes the database updating all the changes that have occurred through the Database manager.
## Table Pages Section
By default, RadSystem Studio creates interfaces (pages) for managing each table in the Database. What is generally known as CRUD (Create, Read, Update and Delete), can be seen in 5 pages: One to list the records, one to see the details of each record, one to Add Records, one to Edit Records and, finally, one to Delete a Record.
![table-pages-section.png](/pages/table-pages-section.png){.align-center}
The Section also offers three buttons for managing the pages:
1. The first button in the section allows you to add a custom page to the project. Among the options in the window, we can choose the name of the page, the type of page (List, Add, Edit or View). If we have a menu configured, we can also choose if the shortcut to be created is a submenu of the main one or if it is created as an independent access in the main menu.
2. The second button allows you to duplicate the selected page.
3. There is also a button for direct access to the page design.

At the bottom we have access to each of the properties that can be applied to a certain page.

For the "List Page", we can configure the following properties:
### Subsection 01 - Page Design
* **AjaxPage**: Allows you to establish whether the page will use the asynchronous JavaScript technique, processing any request to the server in the background.
> To enable ajax search in the list, it is important set to True this option.
{.is-info}

* **PageTitle**: By default, RadSystems Studio uses the table name as the page name. This option allows you to customize the name of the Title that will appear in the List Page.
* **DisplayType**: You can select how the data is presented. Choose between a tabular or a grid format.
* **EmptyRecordMessage**: Allows you to customize the message when there is no data in the table.
### Subsection 02 - Default Query Configuration
* **Join Tables**: Here you can specify your own SQL query or access a window that will help you with its construction.
* **Where**: The option allows you to specify the SQL WHERE clause that allows you to retrieve a data set under a condition.
* **Having**: The option allows you to specify the SQL HAVING clause that allows you to retrieve a data set under a SUM or MAX condition.
* **Order By**: You can specify whether the query is sorted in ascending or descending order and the fields to which it applies.
* **Record Limit**: It allows to specify the number of records to display per page block.
### Subsection 04 - Inline Edit
* **InlineEdit**: Allows you to specify whether it is possible to edit the records on the same list.
* **EditFieldControlType**: Allows you to choose whether the inline edition will be based on what is configured on the Edition page or through a specific data format.
* **UsePopOverDisplay**: Allows you to enable or disable the pop - screen for inline editing.
* **Placement**: The option allows you to specify the position of the popover display on a inline edition.
* **ActivateMode**: You can specify the method by which inline editing is triggered.
* **ShowButtons**: Allows you to specify the position of the buttons that allow inline editing.
### Subsection 05 - Page Components
* **ActionButtonDisplayStile**: Allows you to specify whether to view, edit or delete a record, icons or a drop-down menu will be used.
* **ActionButtonInFront**: You can select if the action buttons will be in front of each row of records or at the end of them.
* **DeleteButton**: Select if the delete record button will be visible.
* **EditButton**: Select if the Edit record button will be visible.
* **ViewButton**: Select if the View record button will be visible.
* **EditButtonText**: Allows you to customize the caption of the Edit button.
* **ViewButtonText**: Allows you to customize the caption of the View button.
* **DeleteButtonText**: Allows you to customize the caption of the Delete button.
* **Export**: Specify if the export selector will be present in the record list view.
* **ExportSettings**: In the pop-up window, you can configure the export formats that will be available as well as specify a custom template or define the page orientation for export, among other options.
* **ExportButtonText**: Allows you to customize the caption of the Export button.
* **ImportData**: In the pop-up window, you can set whether the data import button will be available, define the text selector or the sign used to define the field separation in a CSV data import.
* **ImportButtonText**: Allows you to customize the caption of the Import button.
* **ListSequence**: Specify if a List Sequence will be present in the record list view.
* **IncludeCheckBox**: Specify if a Check Box will be present for each record in list view.
* **Pagination**: Specify if the page number selector will be present in the record list view.
* **PaginationSettings**: Here you can set the pagination style, as well as set if the record counter, page counter and per page record selector will be visible.
### Subsection 06 - Page Modal
* **ModalEdit**: Allows you to set if the modal edition will be available.
* **ModalView**: Allows you to set if the modal view will be available.
### Subsection 07 - Table Design
* **TableBorderStyle**: Allows you to set the border Style of the List Page.
* **TableStripped**: It allows to set if the list of records will be visually divided through separator lines.
* **TableDark**: Allows to apply a dark theme to the records table.
* **TableCompact**: Allows you to set a compact format for the list page.
* **TableHeaderBackground**: Here you can select, in bootstrap format, the style of the background color of the field headers.
* **TableHeaderTextColor**: Here you can select, in bootstrap format, the text colorr of the field headers.
* **TableHoverable**: Allows you to set if the feature of selecting records on mouse over will be available.
* **TableResponsive**: Allows you to set if the Responsive feature of the table will be available.
* **TableCellAlignment**: Allows you to set the alignment of the data in the cells.

For the "View Page", we can configure the following properties:
### Subsection 01 - Page Design
* **AjaxPage**: Allows you to set whether the page will use the asynchronous JavaScript technique, processing any request to the server in the background.
* **PageTitle**: This option allows you to customize the name that will appear as Title in the View page.
* **DisplayType**: Here you can set if the layout of each record and its titles will be horizontal or vertical.
### Subsection 02 - Query Configuration
* **Join Tables**: Let you specify your own SQL query or access a window that will help you with its construction.
### Subsection 02 - Record Events
* **Mail Action Settings**: Here you can set if an email will be sent every time the record is displayed as well as the title, subject and origin of the mail.
> Make sure you have set the default mail configuration in the Project setting option.
{.is-warning}
### Subsection 03 - Page Components
* **EditButton**: Select if the Edit record button will be visible.
* **DeleteButton**: Select if the Delete record button will be visible.
* **EditButtonText**: Allows you to customize the caption of the Edit button.
* **ModalEdit**: Allows you to set if the modal edition will be available.
* **DeleteButtonText**: Allows you to customize the caption of the Delete button.
* **Export**: Let you set if the export selector will be present in the view record.
* **ExportSettings**: In the pop-up window, you can configure the export formats that will be available as well as specify a custom template or define the page orientation for export, among other options.
* **ExportButtonText**: Allows you to customize the caption of the Export button.

For the "Add Page", we can configure the following properties:
### Subsection 01 - Page Design
* **PageTitle**: This option allows you to customize the name that will appear as Title in the Add page.
* **SubmitButtonText**: Allows you to customize the caption of the Add button.
* **EnableCaptchaValidation**: Let you set if the Captcha Validation will be available before add a record.
* **PageCustomValidation**: Let you place your own code for validate when a new record is inserted.
* **EnableAutoCompleteField**: Select if the autocomplete feature will be available.
* **SubForms**: This feature let you add subforms when adding a record. You can Specify the relation type, the name of the child form and the foreing key.
* **FormLayoutType**: Let you select the form layout.
### Subsection 02 - General
* **MessageAfterAdd**: Allows you to customize the message that will be displayed once a record has been added.
### Subsection 02 - Record Events
* **Redirect To After Add**: Let you set the page to which it will be redirected once the record has been added.
* **Mail Action Settings**: Here you can set if an email will be sent every time the record is added as well as the title, subject and origin of the mail.
> Make sure you have set the default mail configuration in the Project setting option.
{.is-warning}
### Subsection 03 - Page Components
* **Load Indicator Settings**: Here you can set the pagination style, as well as set if the record counter, page counter and per page record selector will be visible.

For the "Edit Page", we can configure the following properties:
### Subsection 01 - Page Design
* **PageTitle**: This option allows you to customize the name that will appear as Title in the Edit page.
* **SubmitButtonText**: Allows you to customize the caption of the Edit button.
* **EnableCaptchaValidation**: Let you set if the Captcha Validation will be available for a edited record.
* **PageCustomValidation**: Let you place your own code for validate when a record is edited.
### Subsection 02 - General
* **FormLayoutType**: Let you select the form layout.
* **MessageAfterAdd**: Allows you to customize the message that will be displayed once a record has been edited.
### Subsection 02 - Record Events
* **Redirect To After Add**: Let you set the page to which it will be redirected once the record has been edited.
* **Mail Action Settings**: Here you can set if an email will be sent every time the record is edited as well as the title, subject and origin of the mail.
> Make sure you have set the default mail configuration in the Project setting option.
{.is-warning}
### Subsection 03 - Page Components
* **Load Indicator Settings**: Here you can set the pagination style, as well as set if the record counter, page counter and per page record selector will be visible.

For the "Delte Page", we can configure the following properties:
### Subsection 01 - General
* **PromptMessageBeforeDelete**: Here you can customize the message displayed before a record is deleted.
* **PromptDisplayStyle**: Let you set de Style of the prompt message displayed.
* **Redirect To After Delete**: Let you set the page to which it will be redirected once the record has been deleted.
### Subsection 02 - General
* **Mail Action Settings**: Here you can set if an email will be sent every time the record is deleted as well as the title, subject and origin of the mail.
> Make sure you have set the default mail configuration in the Project setting option.
{.is-warning}
## Table Pages Fields Section
![table-page-fields-section.png](/pages/table-page-fields-section.png)


