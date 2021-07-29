---
title: Records TimeStamps
description: Setup timestamp of your data
published: true
date: 2021-07-29T00:49:59.114Z
tags: record, timestamp
editor: markdown
dateCreated: 2021-07-29T00:49:59.114Z
---

# Records Timestamps
Set the dates when record is created or updated.
These fields will be created if they are not yet exist.
Fields: 
- date_created
- date_update
- date_deleted (Optional)

## Setup
1. Click **Records Timestamps**.
2. In **Record Timestamps** window, select the Database Table you want to put this feature.
3. Check **Enable Record Timestamp on the Table**.
4. Enter **Date Created Field Name**. (default: *date_created*)
5. Enter **Date Update Field Name**. (default: *date_update*)
6. If you want to enable Soft-Delete feature then enter a value in **Date Deleted Field Name**. (default: *date_deleted). Otherwise, leave it as blank
7. (Optional). **Apply to other tables**, the settings in step 3-6 will be applied to all the tables.
8. Click **Okay**
![1.png](/security/recordtimestamp/1.png)
![2.png](/security/recordtimestamp/2.png)

