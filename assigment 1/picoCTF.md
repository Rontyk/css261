## More SQLi:

### 1. Login with Password Only (Without Username)
Try injecting an SQL query that allows login using only the password field

### 2. Identify the Database Name
The database name is **SQLiLite**.

### 3. Discover Tables and Columns
After executing SQL queries, we identify a table named **more_table** which contains a column **flag**.

### 4. Extract the Flag
To retrieve the flag, use SQL injection.


## SQLiLite:

### 1. Login with username **admin' or 1=1--**

### 2. Press F12 and the flag will be written in HTML text
