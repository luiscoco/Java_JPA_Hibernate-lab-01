# JPA Hiberante - Lab 01

## How to run the application

Install MySQL and create a new database 

https://dev.mysql.com/downloads/installer/

To create a new MySQL database named JPA_DB_01, you can run the following SQL command:

```
CREATE DATABASE JPA_DB_01;
```

<img width="682" height="339" alt="image" src="https://github.com/user-attachments/assets/37ad32d0-a549-4354-a9dd-7fc2f83c5843" />

Run VSCode and bavigate into the JPA-LAB-01 folder

Run these two commands:

```
mvn -q -DskipTests package
mvn -q exec:java
```

<img width="1388" height="690" alt="image" src="https://github.com/user-attachments/assets/91e74ff1-3e86-4406-9a2e-f2d705b5fda6" />

<img width="1395" height="715" alt="image" src="https://github.com/user-attachments/assets/27acf09c-fa35-4643-bb0b-78095d9e5333" />

Now we confirm in MySQL database the changes implemented

<img width="812" height="520" alt="image" src="https://github.com/user-attachments/assets/6f8ebeac-c94d-4921-9971-a9c35a341ba3" />


