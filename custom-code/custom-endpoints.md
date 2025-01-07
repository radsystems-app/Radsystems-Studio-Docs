---
title: Custom Endpoints
description: 
published: true
date: 2025-01-07T00:51:14.969Z
tags: endpoint, routes, api
editor: markdown
dateCreated: 2021-08-02T05:07:16.716Z
---

# Custom Endpoints
**Custom Endpoints** is where we can create our own custom method or routes.

## Setup
1. In main RS window, Click **Custom Endpoints**
2. Click **Add New Endpoint** button.
3. **Controller** dropdown: Select which controller our custom code will be written. In this example, I will be using **Orders** controller.
4. **Action Name**: Route path or name (e.g **Testing**).
5. **Request Type**: I will be using **GET** here, but you can POST or ANY if you like.
![1.png](/custom-code/endpoints/1.png)

# Sample Code
Let's try this code below: 
*I will try to fetch all records from my Orders table using the custom code, currently there are 2 records in it.*.

## PHPRad Classic
```php
public function __ACTION_NAME__(Request $request){
        
   $sqltext = "SELECT * FROM Orders";
   $records = DB::select($sqltext);
        
   return $records;
}
```

## PHPRad Vue
```php
public function __ACTION_NAME__(Request $request){
   $sqltext = "SELECT * FROM Orders";
   $records = DB::select($sqltext);
   return $records;
}
```

## NodeRad Vue
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

## PyRad Vue
```py
@__tablename_blueprint.route('__ACTION_PATH__', methods=['GET'])
#AuthRequiredDecorator
def __ACTION_NAME__():
    try:
    sqltext = "SELECT * FROM Orders"
        records = db.session.execute(sqltext).all()
        return jsonify([dict(row) for row in records])
    except Exception as ex:
        return abort(500, str(ex))
```
> **Note: PyRad Vue**
Pay attention with your code indention and it is case-sensitive.
{.is-warning}

## ASPRad Vue
```js
[HttpGet]
        __allowanonymous
        public ActionResult __ACTION_NAME__(){
            try{
                var sqlText = "SELECT * FROM tablename";
                var records =  DB.RawSqlQuery(sqlText);
                return Ok(records);
            }
            catch (Exception ex){
                return StatusCode(500, $"{ex}");
            }
        }
```


# Test the Code
There are multiple ways to test the code:
## PHPRad Classic
For **PHPRad Classic** we need to manually define the a routes in routes/web.php
1. Click **Project Explorer**.
2. Navigate to **routes/web.php**.
3. Inside the **web.php**, add this code below:
```php
Route::get('testing','OrdersController@testing')->name('orders.testing');
```
4. Go to your browser and enter this link. http://localhost:8050/testing 

## PHPRad Vue
For **PHPRad Vue** we need to manually define the a routes in routes/api.php
1. Click **Project Explorer**.
2. Navigate to **routes/api.php**.
3. Inside the **web.php**, add this code below:
```php
Route::get('orders/testing','OrdersController@testing');
```
4. Go to your browser and enter this link. http://localhost:8060/api/orders/testing 
> **NOTE: DEFAULT PORT**
> 8060 - Backend API
> 8050 - FrontEnd
{.is-warning}

## NodeRad Vue
For **NodeRad Vue** you can directly navigate to this link below:
http://localhost:8060/api/orders/testing

> **NOTE: DEFAULT PORT**
> 8060 - Backend API
> 8050 - FrontEnd
{.is-warning}

## PyRad Vue
For **PyRad Vue** you can directly navigate to this link below:
http://localhost:8060/api/orders/testing

> **NOTE: DEFAULT PORT**
> 8060 - Backend API
> 8050 - FrontEnd
{.is-warning}

The output should be like this below:

```php
[
  {
    "id": 1,
    "date": "2021-08-02",
    "order_no": "12345",
    "remarks": "test1"
  },
  {
    "id": 2,
    "date": "2021-08-02",
    "order_no": "12346",
    "remarks": "test2"
  }
]
```