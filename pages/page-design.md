---
title: Design
description: Learn how to customize the output view
published: true
date: 2021-08-05T01:32:22.854Z
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

# Pages, Components and Widgets
![pages-components-widgets-window.png](/pages/pages-components-widgets-window.png)
## Layout Components
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
## View Components
### <span style="color:blue">*Header* Component</span>
![header-component-window.png](/pages/header-component-window.png)
### Component Properties
#### Various
* **Text**: You can specify the title that appears in the page view.
* **Subtittle**: You can set the subtitle that appears in the page view.
* **Tag**: There are six types of titles in bootstrap. Here you can select one of them.
* **Header Class**: You can set the text style, color, margins and padding for the title component in a practical interface with the CSS Class Builder.
![css-class-builder-window.png](/pages/css-class-builder-window.png)
* **Subtitle Class**: You can set the text style, color, margins and padding for the subtitle.
### <span style="color:blue">*Accordion* Component</span>
The  accordion component organizes content within collapsable items. Allows to display only one collapsed item at a time.
![accordion-component-window.png](/pages/accordion-component-window.png)
### Component Properties
#### Various
* **Header Title**: You can set the title of the accordion tab.
* **Header Subtittle**: You can set the subtitle of the accordion tab.
* **Header icon**: You can set an icon for the header title.
* **OpenByDefault**: When set to True, displays the content of a particular Accordion tab when the page loads.
### <span style="color:blue">*TabPage* Component</span>
In the same way as the accordion component, the tab component allows you to organize content in windows.
![tabpage-component-window.png](/pages/tabpage-component-window.png)
### Component Properties
#### 01 - Page Design
* **NavType**: You can set if the nav-bar view will be by pills or tabs.
* **TabOrientation**: Can be set to Horizontal, Horizontal End, Horizontal Center, Vertical or Vertical End.
* **Justified**: Allows to establish if the titles of the tabs will be justified in the view of the page.
* **WrapInCard**: The option allows you to specify if the component will be contained in the Card element.
* **WrapperClass**: You can set the text style, color, margins and padding for the Tab component in a practical interface with the CSS Class Builder.
#### Various
* **PlaceInCard**: You can set if the component will be contained in the Card element.
### Tab Component Properties
![tab-component-window.png](/pages/tab-component-window.png)
#### Various
* **Header Title**: You can set the title of the tab.
* **FormPage**: You can specify which page will be included in the tab view.
* **Header icon**: You can set an icon for the tab.
### <span style="color:blue">*FormWizard* Component</span>
The form wizard is a user interface that allows users to achieve a goal through a series of steps.
![formwizard-component-window.png](/pages/formwizard-component-window.png)
### Component Properties
#### 01 - Page Design
* **WizardStyle**: There are three predefined styles that can be used as a choice: dots, circles and arrows.
* **Header Title**: You can set the title for the form wizard.
* **Header Subtittle**: You can set the subtitle for the form wizard.
* **ThemeColor**: You can choose the color for the theme that will be applied to the form wizard.
* **WrapInCard**: The option allows you to specify if the component will be contained in the Card element.
* **WrapperClass**: You can set the text style, color, margins and padding for the component through the CSS Class Builder.
### Step Component Properties
* **Header Title**: You can set the title for the step tab of the form wizard.
* **Header Subtittle**: You can set the subtitle for the step tab of the form wizard.
* **FormPage**: You can specify which page will be included in the step view.
* **Header icon**: You can set an icon for the step tab.
* **PreviousButtonText**: Here you can set a caption for the button that the component includes to access the previous step.
* **NextButtonText**: Here you can set a caption for the button that the component includes to access the next step.
### <span style="color:blue">*Modal* Component</span>
The modal component provides an interface to create dialogs, including forms.
![modal-component-window.png](/pages/modal-component-window.png)
### Component Properties
#### 01 - Page Design
* **WrapInCard**: The option allows you to specify if the component will be contained in the Card element.
* **WrapperClass**: You can set the text style, color, margins and padding for the component through the CSS Class Builder.
### Modal Contents Component Properties
![modalcontents-component-window.png](/pages/modalcontents-component-window.png)
#### Various
* **Button Text**: You can set the caption for the modal button.
* **ButtonClass**: Bootstrap provides several classes for styling buttons. Here you can specify one of these or your own.
* **Header Title**: You can set the title for the modal window.
* **Header icon**: You can set an icon for the title of the modal window.
* **ModalSize**: You can specify a bootstrap class to set the size of the modal window.
* **Show Backdrop**: By default the system dulls the background to give emphasis to the modal window, you can deactivate the option through this property.
## Page Filter Components
### <span style="color:blue">*Button* Component</span>
Buttons allow to link to a specific page.
![button-component-window.png](/pages/button-component-window.png)
### Component Properties
#### 01 - Page Design
* **WrapInCard**: The option allows you to specify if the component will be contained in the Card element.
* **WrapperClass**: You can set the text style, color, margins and padding for the component through the CSS Class Builder.
#### 01 - Page Records
* **PageLink**: You can set the page to link.
#### 02 - Design
* **Text**: You can set the caption for the button.
* **icon**: You can set an icon for the caption of the button.
* **ButtonClass**: Bootstrap provides several classes for styling buttons. Here you can specify one of these or your own.
* **OpenAsLink**: You can specify whether the button will redirect to the page in the navigation way, as an ajax modal window or inserted in the same view.
### <span style="color:blue">*Search Field* Component</span>
Add a search field on the page, allowing the user to make certain queries.
![search-component-window.png](/pages/search-component-window.png)
### Component Properties
#### 01 - Search
* **Use Dropdown Search**: Enables drop-down search in the component.
* **Placeholder**: Allows you to set the text label placed inside a field of a form.
* **Search List Template**: Through the code editor, it allows to customize the ajax search format.
### <span style="color:blue">*Range Field* Component</span>
Add a Slide Range control to the page to filter the data by the range established in it.
![rangefield-component-window.png](/pages/rangefield-component-window.png)
### Component Properties
#### 01 - Data Bind
* **FieldName**: The property allows select the field by which the data will be filtered.
* **DoubleRange**: Set a double slider for the component to filter data through two variables.
* **SingleRangeComparator**: You can define comparison operator for data filtering.
* **MinValue**: Allows you to set the minimum value of the range component.
* **MaxValue**: Allows you to set the maximum value of the range component.
* **LabelPrefix**: It allows to indicate a prefix for the label of the minimum and maximum values.
* **LabelSuffix**: It allows to indicate a suffix for the label of the minimum and maximum values.
* **ValueStep**: Allows to set the jump between values of the established range.
* **MaxInterval**: Allows you to set the maximum range that is allowed between the minimum and maximum values.
* **MinInterval**: Allows you to set the minimum range that is allowed between the minimum and maximum values.
* **DefaultSelected**: Allows you to set the default value of the sliding indicator.
#### 01 - Page Design
* **WrapInCard**: The option allows you to specify if the component will be contained in the Card element.
* **WrapperClass**: You can set the text style, color, margins and padding for the component through the CSS Class Builder.


