---
title: Global Settings
description: 
published: true
date: 2021-08-13T11:11:33.690Z
tags: 
editor: markdown
dateCreated: 2021-08-13T11:11:33.690Z
---

# Global Settings

Global Settings are the default behavior of your project upon creation.
> Modifying the default setup will not affect the settings of the previously created projects.
{.is-info}


## New Project 
- ProjectDefaultDirectory - Default projects directory location.
- DefaulIconPack - Select which icon should be set as default.

## Default Database Settings 
- Database - Type of database (MYSQL/MARIADB, MSSQL, SQLITE, POSTGRES)
- DatabaseHost - Location of the database (e.g localhost).
- DatabaseUsername - Username of the Database.
- DatabasePassword - Password of the database.
- DatabasePost - The default database port.

## General Settings 
- HideLaravelDatabaseTables - (True / False)
- PHPDateDefaultTimeZone
- EnableAppDebug (True / False)
- ShowPagePreloader (True / False)
- DefaultAppTheme 
- FormFieldValidationRequired (True / False)
- ListPageFieldsSortable (True / False)
- IncludePageFooter (True / False)
- PageSectionContainerClass (container / container-fluid)
- QueryLimit
- AddPageSubmitButtonText
- EnableCaptchaValidation (True / False)
- EditPageSubmitButtonText
## Page Inline Edit Settings
- InlineEdit (True / False)
Enable inline edit on all pages
- UsePopoverDisplay (True / False)
Use Popover container for inline edit on all page fields.
- Placement (Top, Right, Bottom, Left)
Position of the Popover container. This only applies when UsePopoverDisplay=True
- ShowButtons (Left, Bottom, False)
Inline edit action button position, if set to false, buttons will not be display and will requires user to press the 'Enter Key' before value is saved.
- ActivateMode (dblClick, Click, MouseEnter, Button)
Event use to activate inline edit on a page field.
- EditFieldControlType
Control type use for the edit. All configuration applied to a field in the Edit Page will also bbe applied to inline edit field.

## Page Report
This will define if the page can be exported to the following format:
- WORD
- EXCEL
- IMAGE
- CSV
- PDF

## Page Settings
- AjaxPage (True / False)
- ListPageDisplayType (Tabular / Grid)
- ActionButtonDisplayStyle (Icons / Dropdown)
- ActionButtonInFront (True / False)
- ExportButton (True / False) - Show / Hide Export Button
- ExportButtonText - This is the label or caption of the button in the List Page
- ViewPageExportButtonText - This is the label or caption of the button in the View Page
- JsonDataImport (True / False)
- CSVDataImport (True / False)
- ImportButtonText - Label or Caption of the import button.
- ListSequence (True / False)
- ListCheckBox (True / False)
- EmptyRecordMessage - Message to be displayed when there is no result record found.
- PromptMessageBeforeDelete - Confirmation message.
- PromptDisplayStyle - Define the way the message is display.
- MessageAfterDelete
- MessageAfterUpdate
- MessageAfterAdd
- FormLayout
- EditbuttonText - Label or caption of the edit button in the list.
- ViewButtonText - Label or caption of the view button in the list.
- DeleteButtonText - Label or caption of the delete button in the list.
- ViewPageEditButtonText - Label or caption of the edit button in the View Page.
- ViewPageDeleteButtonText - Label or caption of the delete button in the View Page.
- ModalEdit - If set to true, a modal window will display upon editing the record.
- ModalAdd - Define how the add page will be displayed.
- ModalView - If set to true, a modal window will display upon viewing the record.

## Table Settings
- TableBorderStyles
- TableStriped
- TableCompact
- TableHoverable
- TableDark
- TableHeaderBackgroundVariant
- TableHeaderTextVariant

## Pagination Settings
- PaginationStyle
- LoadMoreButtonText
- LoadCompletedText
- LoadIndicatorType
- LoadIndicatorColor
- LoadIndicatorSize
- LoadIndicatorText

## Misc
- FormAutoComplete
- PRINT