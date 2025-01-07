---
title: Publish
description: Guide on publishing the application
published: true
date: 2025-01-07T00:51:48.050Z
tags: 
editor: markdown
dateCreated: 2021-08-23T04:21:42.799Z
---

# Publish Project
Guide for publishing the project.
![2.png](/publish/2.png)

## Test Project
To test the project you created, you can just click directly the Publish tab and it will automatically generate necessary files to run your program.

![1.png](/publish/1.png)
![3.png](/publish/3.png)

It will generate two folders in your root project directory i.e backend and frontend.
![pub_api4.png](/publish/pub_api4.png)

## Publish To Production
Tick the publish to production checkbox to generate the **final build** of your project.
- It will create `dist` folder under `frontend`.
- Inside dist folder is another folder that holds what platform it is intended for.

>  Tip: 
Built files are meant to be served over an HTTP server
Opening index.html over file:// won't work
{.is-warning}

> Tip: 
You can use `"$ quasar serve"` command to create a web server, both for testing or production. Type `"$ quasar serve -h"` for parameters. 
{.is-primary}

> Tip: 
Also, an npm script (usually named "start") can be added for deployment environments. If you're using Vue Router "history" mode, don't forget to specify the `"--history"` parameter: 
`"$ quasar serve --history"`
{.is-primary}



## App Platform
You can choose different platform below without touching the source code:
- SPA(default)
- PWA
- Desktop App (via Electron)
- Mobile App (via Cordova)

## Api Platform
Api Platform is a backend of your project that responsible in communicating with your database.

A good thing in RadSystems is same with the App Platform you can just switch which Api platform you want to create on the fly.

- PHP-Laravel
- Python Flask
- NodeJS Express
- ASP.Net Core

## Preview in Browser
Clicking this button will open your app in a browser.
![prev.png](/publish/prev.png)

## Re-Publish Project
Clicking this button will re-publish your project.
![repub.png](/publish/repub.png)

## Browse Project Folder
Clicking this button will open your project directory.
![brow.png](/publish/brow.png)

## Publish API Documentation
![brow.png](/publish/pub_api.png)
This will generate a documentation of your API.

![pub_api2.png](/publish/pub_api2.png)

API documentation will be save at the root directory of your project.
![pub_api3.png](/publish/pub_api3.png)

Clicking **Open in browser** to view the documentation.

![pub_api4.png](/publish/pub_api5.png)

