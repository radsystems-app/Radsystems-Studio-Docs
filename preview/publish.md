---
title: Publish
description: Guide on publishing the application
published: true
date: 2021-08-23T07:10:19.433Z
tags: 
editor: markdown
dateCreated: 2021-08-23T04:21:42.799Z
---

# Publish Project
Guide for publishing the project.

## Publish To Production
Tick the publish to production checkbox to generate the final build of your project.
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
## Api Platform
## Preview in Browser
## Re-Publish Project
## Browse Project Folder
## Publish API Documentation