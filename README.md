# Inventory Management System 📦

## Description 📝
The Inventory Management System is a Java-based application developed using NetBeans IDE, with MySQL database managed through XAMPP Server.Revision and rework by BONFIRE for more info kindly reach out to the new owner by the provided link below 

Portfolio:https://github.com/Jury018/MY-PORTFOLIO-

## Features ✨
- Add, update, delete inventory items 🖥️
- Track inventory levels in real-time 📊
- Generate sales and inventory reports 📈
- User authentication and authorization 🔒
- Database backup and restore 💾

## Installation ⚙️

### Prerequisites
- [Java JDK](https://www.oracle.com/java/technologies/javase-downloads.html) ☕
- [NetBeans IDE](https://netbeans.apache.org/download/index.html) 🖥️
- [XAMPP](https://www.apachefriends.org/index.html) 🛠️

### Setup
1. **Clone the repository:**
    ```bash
    git clone https://github.com/harishy0406/Inventory-Management-System
    ```

2. **Open the project in NetBeans:**
    - Launch NetBeans IDE.
    - Navigate to `File -> Open Project`.
    - Select the cloned project directory.

3. **Setup XAMPP:**
    - Start Apache and MySQL modules in XAMPP control panel.
    - Open phpMyAdmin and create a database named `inventory_db`.
    - Import the `inventory_db.sql` file located in the project's `db` directory to set up the database schema and initial data.

4. **Configure database connection:**
    - Open `DatabaseConnection.java` file.
    - Update the database URL, username, and password as per your XAMPP setup.
    ```java
    String url = "jdbc:mysql://localhost:3306/inventory_db";
    String user = "root";
    String password = "";
    ```

## Usage 🚀
1. **Run the project:**
    - In NetBeans, right-click on the project and select `Run`.

2. **Login:**
    - Use the default admin credentials to login:
      - Username: `admin`
      - Password: `admin`

3. **Navigate through the system:**
    - Add, update, delete inventory items through the provided interfaces.
    - Generate and view reports for inventory and sales.

## Snapshots 📸
Here are some snapshots of the project:

### Login Page
![image](https://github.com/harishy0406/Inventory-Management-System/assets/142865295/991f2085-958a-4f25-b656-a794429cb5cb)

## Registeration page
![image](https://github.com/harishy0406/Inventory-Management-System/assets/142865295/4f110363-27b9-4035-ba5b-53219cce1035)

### Dashboard
![image](https://github.com/harishy0406/Inventory-Management-System/assets/142865295/06b4d825-1479-4fc4-b673-30a7e632af41)

### Inventory Management
![image](https://github.com/harishy0406/Inventory-Management-System/assets/142865295/64884ff5-73e1-49e6-a08c-01eb9143c502)
![image](https://github.com/harishy0406/Inventory-Management-System/assets/142865295/3c7614bf-a892-43d7-bfa2-65d2fd9e2045)
![image](https://github.com/harishy0406/Inventory-Management-System/assets/142865295/fdb69135-ee7b-4d7e-a63b-2ab6d8e0d2db)
![image](https://github.com/harishy0406/Inventory-Management-System/assets/142865295/30f61a99-f9bd-4978-bec1-7bd3260cd2e4)
![image](https://github.com/harishy0406/Inventory-Management-System/assets/142865295/129df3bb-e6d5-4e33-8125-7f6010c26940)

Thank you for visiting my Inventory Management System project! 😊 Feel free to explore and reach out if you have any questions or opportunities. 📫
