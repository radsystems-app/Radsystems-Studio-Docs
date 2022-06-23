---
title: Eventos de Páginas
description: Maneje acciones en las Páginas
published: true
date: 2022-06-23T20:53:21.012Z
tags: 
editor: markdown
dateCreated: 2022-06-23T20:53:21.012Z
---

# Page Events
**Page Events** where you can insert a code that will run before and after the main action function.

![page-events.png](/page-events/page-events.png)

# How to Use
1. Click **Page Events** in the RS Toolbar - it will pop up the Page Events window.

![1.png](/page-events/1.png)

2. Click and expand the Pages Tree and click **"Before..."** or **"After..."**.

![2.png](/page-events/2.png)

3. Click **Edit Page Event** button to enable the code window.

![3.png](/page-events/3.png)

4. Put your code inside the function given.
5. On the right side, there is a built-in code snippet that you can use just by double clicking it.

![4.png](/page-events/4.png)
![5.png](/page-events/5.png)

> Note: If you want to remove your page event code, click **Clear Page Event**.
{.is-info}


# Example
For our example we will be creating a Log System where we can track every new Todo added.

1. Create Database, name it: **todo-db**
2. Create the first table, name it: **Todos**
3. Create 2 fields for Todos table
- **id** *(INT AUTO_INCREMENT PRIMARY NOT NULL)*
- **todo** *(VARCHAR(255) NOT NULL)*

4. Create the second table, name it: **Logs**
5. Create 4 fields for Logs table
- **id** *(INT AUTO_INCREMENT PRIMARY NOT NULL)*
- **dt** *(TIMESTAMP DEFAULT CURRENT_TIMESTAMP)*
- **action** *(VARCHAR(15) NOT NULL)*
- **todo** *(VARCHAR(255) NOT NULL)*

6. In RS Studio, click **Page Events** in the toolbar.
7. Expand the **Pages -> Todos -> Add** tree and click **AfterAdd**.
8. Click **Edit Page Event**.
9. Place your code inside the function.
10. Use the code below for specific language you are using.
11. Click **Okay** to save.
12. In RS Studio, click **Publish** or **Re-publish Project**.

> So everytime you add a new Todo in the Todos module, it saves a log record on the Logs module.
{.is-success}


## PHPRad Classic (PHP Laravel + Boostrap Jquery)
```
    private function afterAdd($record){
        //enter statement here
        
        $modeldata = ['action' => 'Add', 'todo' => $record['todo']];
        DB::table('Logs')->insert($modeldata);
    }
```

## PHPRad Vue (PHP Laravel + Quasar Vue)
```
    private function afterAdd($record){
        //enter statement here
        
        $modeldata = ['action' => 'Add', 'todo' => $record['todo']];
        DB::table('Logs')->insert($modeldata);
    }
```

## NodeRad Vue (NodeJS Express + Quasar Vue)
```
async function afterAdd(record, req){
    //enter statement here
    
    let tableModel = models.Logs;  //Logs is the name of the table
    let modeldata = {
        action: 'Add',
        todo: record.todo
    }
    
    await tableModel.create(modeldata);
}
```

## PyRad Vue (Python Flask + Quasar Vue)
```
def after_add(record):
    # statement here
    
    new_record = Logs(action="Add", todo=record.todo)
    db.session.add(new_record)
    db.session.commit()
```

## ASPRad Vue (ASP .Net Core + Quasar Vue)
```
private void afterAdd(Todos record){
   //enter statement here
            
   var modeldata = new Logs(); //Logs is the tablename or modelname
            
	 modeldata.action = "Add";
   modeldata.todo = record.todo;
   DB.Logs.Add(modeldata);
   DB.SaveChanges();
}
```