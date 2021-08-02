---
title: Custom Endpoints
description: 
published: true
date: 2021-08-02T05:07:16.716Z
tags: endpoint, routes, api
editor: markdown
dateCreated: 2021-08-02T05:07:16.716Z
---

# Custom Endpoints
**Custom Endpoints** is where we can create our own custom routes.

## Setup
1. In main RS window, Click **Custom Endpoints**
2. Click **Add New Endpoint** button.
3. **Controller** dropdown: Select which controller our custom code will be written.
4. **Action Name**: Route path or name
![1.png](/custom-code/endpoints/1.png)

## NodeRAD Code
5a. Let's try this code below: 
*I will try to fetch all records inside of my Orders table using the custom code*.
```js
router.get('__ACTION_PATH__', async (req, res) => {  
    try{
        let sqltext = `SELECT * FROM Orders` ;
        let records = await sequelize.query(sqltext, {type: sequelize.QueryTypes.SELECT });
        return res.ok(records);
    }
    catch(err) {
        return res.serverError(err);
    }
});
```

6. To check, we can navigate directly to our browser's URL
http://localhost:8060/api/orders/testing

> **Takenote: DEFAULT PORT**
> 8060 - Backend API
> 8050 - FrontEnd
{.is-warning}

![2.png](/custom-code/endpoints/2.png)