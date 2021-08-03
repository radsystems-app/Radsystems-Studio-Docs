---
title: Design
description: Learn how to customize the output view
published: true
date: 2021-08-03T01:26:44.659Z
tags: 
editor: markdown
dateCreated: 2021-08-03T00:07:05.388Z
---

# Page Design
RadSystem Studio uses the Bootstrap Layout components to position items on the browser view. In this way, it favors the device-sensitive, responsive or mobile-first design, which adapts to the size of the screen where a web is displayed.
This is one of the most powerful features of RadStudio Systems.
![design-access-window.png](/pages/design-access-window.png)
There are two ways to enter Page Design.
1. Click on "Page Design" tab.
2. Click on the direct access button to the design of the selected page.
![page-design-window.png](/pages/page-design-window.png)

## Pages, Components and Widgets
![pages-components-widgets-window.png](/pages/pages-components-widgets-window.png)
### Layout Components
### <span style="color:blue">*Row* Component</span>
The Row component is a wrapper for columns. In Bootstrap, the "row" class is used mainly to hold columns in it. Use it to create horizontal groups of columns.
![row-container-window.png](/pages/row-container-window.png)
### Component Properties 
#### 01 Page Design
- **SectionHeaderTitle**: Allows you to set the title for a row.
- **WrapInCard**: In Bootstrap, a card is a flexible and extensible content container. The option allows you to specify if the row will be contained in the Card element.
- **SectionClass**: You can specify a bootstrap class to set the background, text color, padding, and so on. or create and specify your own class for the section.
- **ContainerClass**: You can specify a bootstrap class to set the background, text color, padding, and so on. or create and specify your own class for the container.
- **BorderSeparator**: Indicates whether a border will be present in the page view.
- **RowClass**: You can specify a bootstrap class to set the background, text color, padding, and so on. or create and specify your own class for the Row.
### <span style="color:blue">*Column* Component</span>
The Column component in Bootstrap is a class that indicate the number of columns you'd like to use out of the possible 12 per row. In the Grid System of Bootstrap, content must be placed within columns and only columns may be immediate children of rows
![column-component-window.png](/pages/column-component-window.png)
### Component Properties
#### Various
* **ColumnWidthClass**: You can use Bootstrap classes to set the width of a 12 possible columns per row.
* **ResetGrids**: You can specify if grids are reset in bootstrap.
* **Has Form**: Allows you to specify if the page contains a form to enable the submit button.
* **Form Submit Button Text**: If the page contains a form, you can set the name of the submit button.
