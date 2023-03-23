# trainee_backend
Nodejs,MySQL
### For the clone this backend part 
```
$ git clone https://github.com/DabhiDhruvraj/trainee_backend
```
### Project structure for backend
```
/server
.gitignore
package.json
server.js
package-lock.json
```
### For Start backend part
```
$ cd server
npm i
node server.js
```
### our backend server is running on port number 3001
### For backend part we use MySQL Database.
## For download MySQL
```
$ sudo apt-get install mysql-server
```
## For check version of MySQL
```
$ mysql --version
```
### For our backend part we create Database employeedb
```
CREATE DATABASE employeedb;
USE employeedb;
```
### We create a table 'employees' inside our database for storing our employees information.
```
CREATE TABLES employees;
```
## After enter the employee detail we can see the employee information.
### Screenshot 
![Screenshot from 2023-03-23 15-04-10](https://user-images.githubusercontent.com/122424247/227208226-6e6ab3f3-aa46-49d6-abcb-1e0adb87715a.png)
### Also we can update the user informtion and delete the user.
### It will also update in our database

![Screenshot from 2023-03-23 18-21-28](https://user-images.githubusercontent.com/122424247/227210112-ddcce163-8c3b-433f-b8b4-54806ac310c1.png)





