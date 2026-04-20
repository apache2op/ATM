# 💳 ATM Management System (Java)

A full-featured **ATM Management System** built using **Java**, designed with strong **OOP principles**, secure authentication using **JWT**, and seamless **MySQL database integration** via JDBC. The project uses **Java Swing (JFrame)** to create a graphical user interface.

## 🚀 Features

* 🔐 Secure Login & Signup System
* 💰 Balance Enquiry
* ➕ Deposit Money
* ➖ Withdraw Money
* ⚡ Fast Cash Functionality
* 📄 Mini Statement
* 🔁 Transaction History
* 🔑 PIN Change
* 🖥️ GUI built using **JFrame (Java Swing)**

## 🛠️ Tech Stack

* **Language:** Java (JDK 21)
* **GUI Framework:** Java Swing (**JFrame**)
* **Core Concepts:** OOP (Encapsulation, Inheritance, Abstraction, Polymorphism)
* **Authentication:** JWT (JSON Web Token)
* **Database:** MySQL
* **Connectivity:** JDBC (MySQL Connector)
* **Libraries Used:**

  * `mysql-connector-java`
  * `jcalendar`

## 📁 Folder Structure

```bash
ATM/
│
├── src/
│   ├── icons/
│   │   ├── a.png
│   │   ├── atm.jpg
│   │   └── logo.jpg
│   │
│   └── prog/
│       ├── BalanceEnquiry.java
│       ├── Conn.java
│       ├── Deposit.java
│       ├── FastCash.java
│       ├── Login.java
│       ├── MiniStatement.java
│       ├── Pin.java
│       ├── Signup.java
│       ├── Signup2.java
│       ├── Signup3.java
│       ├── Transactions.java
│       └── Withdrawl.java
│
└── Referenced Libraries/
    ├── mysql-connector-java
    └── jcalendar
```

**Copy/paste the files accordingly to this folder structure**

## 🧠 OOP Concepts Applied

* **Encapsulation:** Protecting sensitive user data (PIN, account details)
* **Abstraction:** Hiding internal logic (like DB operations)
* **Inheritance:** Reusability across transaction-related classes
* **Polymorphism:** Flexible method handling


## 🔗 Database Integration

* Uses **JDBC** to connect Java application with MySQL
* Stores:

  * User account details
  * Transaction history
  * Authentication data

📌 Configure your database credentials inside `Conn.java` before running.


## 🔐 Authentication (JWT)

* Implements **JWT-based authentication**
* Ensures secure session handling and user validation


## ⚙️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/apache2op/ATM.git
   ```

2. Open in Eclipse / IntelliJ IDEA

3. Add required JAR files:

   * MySQL Connector
   * JCalendar

4. Install and Setup MySQL Workbench: https://dev.mysql.com/downloads/installer/

5. Run `Login.java`


## ⭐ Contribute

Contributions are welcome!
Fork the repo and submit a pull request 🚀

## 📜 License

This project is licensed under the MIT License

