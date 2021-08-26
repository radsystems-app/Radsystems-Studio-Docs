---
title: Publish
description: Guide on publishing the application
published: true
date: 2021-08-26T07:38:20.184Z
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
## Re-Publish Project
## Browse Project Folder
## Publish API Documentation