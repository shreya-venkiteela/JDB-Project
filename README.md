# JPDB Project
## *A small project done using JsonPowerDB (JPDB) for simple database operations(CRUD). It includes creation of a web page using JasonPowerDB in NetBeans.*
|               Content                          | 
| ---------------------------------------------- |
| 1. What is JsonPowerDB?                        | 
| 2. Benefits of using JsonPowerDB               |
| 3. CRUD database operations.                   |
| 4. Code for creating a web form using NetBeans |
### What is JsonPowerDB?
##### JsonPowerDB is a Database Server with Developer friendly REST API services. It's a High Performance, Light Weight, Ajax Enabled, Serverless, Simple to Use, Real-time Database. Easy and fast to develop database applications without using any server side programming / scripting or without installing any kind of database.

### Benefits of using JsonPowerDB
##### 1. Minimum Development Cost
##### 2. Minimum Time to Market
##### 3. Maximum Data Processing Performance
##### 4. Technology Futuristic
##### 5. Minimize Total Cost of Ownership.

###CRUD Database Operations
### 1. PUT Command *is used to Create or Insert a record.*
```
{
    "token": "90938547|-31948829580346324|90947035",
    "cmd": "PUT",
    "dbName": "Employee",
    "rel": "EMP-Rel",
    "jsonStr": 
    {
        "name": "Sreya",
        "email": "shreya.venkiteela11@gmail.com"
    }
}
```
### 2. GET Command *is used to Retrieve a Record.*
```
{
    "token": "90938547|-31948829580346324|90947035",
    "cmd": "GET",
    "dbName": "Employee",
    "rel": "EMP-Rel",
    "jsonStr":
    {
        "name": "Sreya",
    }
}
```
### 3. Update Command *is used to update a record in a database.*
```
{
    "token": "90938547|-31948829580346324|90947035",
    "cmd": "UPDATE",
    "dbName": "Employee",
    "rel": "EMP-Rel",
    "jsonStr": {
       "1":
       {
        "name": "venkiteela",
        "email":"gargee@gmail.com",
       }
       
   }
}
```
### 4. Remove Command *is used to remove a record from a database.*
```
{
    "token": "90938547|-31948829580346324|90947035",
    "cmd": "REMOVE",
    "dbName": "Employee",
    "rel": "EMP-Rel",
    "record": 1
}
```

### Code for Creating a Web Form using NetBeans
