---
title: User Record Management
description: Setup User Record Management
published: true
date: 2021-07-29T00:22:52.308Z
tags: security, record, management
editor: markdown
dateCreated: 2021-07-28T03:46:28.160Z
---

# Record Management
This allow user to Manage records that belongs to them.

## Pre-requisite
- The target table must contain a field that identify the user (*e.g, user_id*).
In this example we will be using the folowing tables:
- **Order table** - is our target table.
- **Users table** - where all the users information reside (Note: this table is the one we use in Authentication process)

# Setting Up
1. Create 1 **field: user_id(INT)** in Order Table.
	- Click **Manage Database Table**.
	- In **Manage Database** window at the left side, select the **Order** table.
	- In right side, you should see the all fields of that Order table, now click **Add Field**.
	- Enter **Fieldname**: user_id and FieldType: INT.
	- Click **Save Changes**.
![1.png](/security/recordmanagement/1.png)
  
2. Modify the Add Page of Order Module, and put a default value in user_id field to and **ID** of a logged-in user.
	- Select **Order**.
	- Select **Add Page**.
	- Select **user_id** field, Checked the AddPage, Unchecked the EditPage.
	- In the **Control Properties**, set the following:
		- Display: **none**
		- DefaultValue: **--req.user.id--**
![2.png](/security/recordmanagement/2.png)

Now everytime the logged user add new data to the **Order** table, their id will be recorded.

3. Click **User Record Management**.

4. In **User Record Settings** window, select **Order** table and set the following:
- User Record Field: user_id (*This is the **user_id** we created earlier in Order table*)
- Matched User Field: req.user.id (*This is the **id** in Users table*)

5. **List User Records Only**: Leave it as checked by default.
![4.png](/security/recordmanagement/4.png)

# Try it out
Now, let's try our application, in this example i have my 2 users:
- User1 with the id=4
- User2 with the id=6

![5.png](/security/recordmanagement/5.png)
We'll check if the specific user can only see his id in user_id field record in the Order table.

As you can see, Users can only see their own encoded data.
![user1.png](/security/recordmanagement/user1.png)
![user2.png](/security/recordmanagement/user2.png)