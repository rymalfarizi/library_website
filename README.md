# Library Website
Nama : Rayhan Muhammad Alfarizi

NIM  : 21060122120016

Clone repository using terminal or git bash in any folder that you want
```
git clone https://github.com/rymalfarizi/library_website.git
```
## How to Run Website in your localhost

## Install Mysql
Guide and Link Installation: https://dev.mysql.com/doc/mysql-installation-excerpt/5.7/en/installing.html
## Install Xampp
Link installation: https://www.apachefriends.org/download.html 

### How to make Database
1. Open Xampp Control Panel
2. Then, start module Apache and MySql

   ![image](https://github.com/user-attachments/assets/fe6b691a-c4fa-4341-931a-7c176a77085f)
3. Open terminal or command prompt
4. Type:
   ```shell
   cd "C:\Program Files\xampp\mysql\bin"
   ```
5. Type:
   ```shell
        mysql -u root -p
   ```
6. After the password appears, just press enter
7. Type
   ```shell
   CREATE DATABASE crud_sql
   ```
   ```shell
   USE DATABASE crud_sql
   ```
   ```shell
   CREATE TABLE `books` (
     `id` int(11) NOT NULL PRIMARY KEY AUTO_INCREMENT,
     `name` varchar(100) COLLATE utf8mb4_unicode_ci NOT NULL,
     `author` varchar(50) COLLATE utf8mb4_unicode_ci NOT NULL,
     `created_at` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP,
     `updated_at` timestamp NOT NULL DEFAULT CURRENT_TIMESTAMP ON UPDATE CURRENT_TIMESTAMP
   ) ENGINE=InnoDB DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_unicode_ci;
   ```
   Note: You can change database name but you have to change database name in file lin/db.js in variable connection

### Install Package
Install the required packages by running it in the terminal:
```shell 
npm ci
```

### How to run website
To run on localhost, type in the terminal:
```shell
npm start
```

## Output
Main Menu
![image](https://github.com/user-attachments/assets/b0a77143-7564-4508-a63a-99dfd75b6a94)

Books Catalog
![image](https://github.com/user-attachments/assets/0cf0cca9-da4e-4dbc-8bac-19b13bb33adb)

Add book
![image](https://github.com/user-attachments/assets/eeb63c20-c22e-4fa9-adbf-c05268d7eef2)

Edit book
![image](https://github.com/user-attachments/assets/ee2b5d9b-4e55-4e14-8e34-86b5b4992268)

## LICENCE
You can download the project, modify the code and use it anywhere you want without re-posting to your blog. Happy Coding :)

Thank you.
"# website-perpustakaan" 
