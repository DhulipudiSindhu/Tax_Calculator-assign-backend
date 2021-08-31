# Backend Database

Given two files `app.js` and a database file `userData.db` consisting of three tables `salary` and `user`.

Write APIs to perform operations on the tables `user`, `salary` only after authentication of the user.

The columns of the tables are given below,

**User Table**

| Columns    | Type    |
| ---------- | ------- |
| username   | VARCHAR |
| password   | VARCHAR |


**Salary Table**

| Columns       | Type    |
| ------------- | ------- |
| bsa           | INTEGER |
| lta           |INTEGER  |
| hra           | INTEGER |
| fa            | INTEGER |
| inv           | INTEGER |
| rent          | INTEGER |
| city_type     | VARCHAR |
| med           | INTEGER |

You can use your previous code if required.

#### Sample Valid User Credentials

```
{
  "username": "sindhu",
  "password": "sindhu@2021"
}
```


Use `npm install` to install the packages.

**Export the express instance using the default export syntax.**

**Use Common JS module syntax.**
