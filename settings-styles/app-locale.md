---
title: App Locale
description: Multi Language Configuration
published: true
date: 2024-10-26T02:47:06.409Z
tags: 
editor: markdown
dateCreated: 2021-08-13T22:38:36.327Z
---

# App Locale
One of the nice features in **RadSystems** is you can use different languages in your project on the go either multi or single default.

## Single Language
- Upon creation of the project, select your desired language for your  project in **Default Language** dropdown.

## Enable Multi Language
- Upon creation of the project, tick **Enable Multi Language** checkbox
Note: You cannot switch back to Single Language once setup and vise versa

## Set Default Language
`Project Settings -> Misc -> Default Locale`

## Modify Languages and Phrases
1. In **RS IDE**, click **App Locale.**
2. Enable or Disable languages by ticking the checkboxes.
3. If you want to edit the translation, 
   - Click the specific languages
   - Click the Key
   - Modify the Phrase
   - Click Okay button

![applocal.png](/settings-style/applocal.png)

## Built-In Supported Languages
- French
- Russian
- Chinese
- Italian
- Hindi
- Portuguese
- German
- Spanish
- Arabic

![single_language.png](/settings-style/single_language.png)
![multi_language.png](/settings-style/multi_language.png)

## Custom Language
We can also add custom language to our project
1. Go to your frontend folder
`frontend -> src -> i18n`

2. Create a folder for your custom language.
> Note: You can copy the existing one and modify its content.
{.is-info}


3. Once you create your new custom language folder/file, you need to inform your project by adding the import command to index.js in `frontend -> src -> i18n\index.js`
> Note: In this example I use NodeRad.
{.is-info}

![custom.png](/settings-style/custom.png)

4. Edit `frontend -> src -> menus.js`. In the locales object add `"custom": "Custom"`.
![custom2.png](/settings-style/custom2.png)

5. Re-publish your project, and you should see the custom languages added in the dropdown.