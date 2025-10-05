👇

<h2>💳 ATM Transaction Management System</h2>
<h1>📘 Overview</h1>

The ATM Transaction Management System is a web-based application designed to simulate ATM transactions such as Deposit and Withdrawal operations. It helps manage cash flow, track account activities, and maintain the ATM’s available balance dynamically.

This project demonstrates Spring Boot + Java + MySQL integration with a simple and user-friendly frontend for performing and tracking transactions in real-time.

<h1>🚀 Features</h1>

💰 Deposit & Withdraw money with real-time balance updates.

📊 Track all transactions with details such as:

Account Number

Transaction Type

Transaction Amount

Updated ATM Cash Balance

🔎 Filter Transactions by:

Deposit

Withdraw

Amount greater than a specified value

🧾 Dynamic cash balance displayed at the top.

🎨 Responsive and clean UI built for smooth user experience.

🧠 Technologies Used

Frontend:

HTML5, CSS3, JavaScript

Bootstrap 5 (for UI components)

Backend:

Java (Spring Boot Framework)

Spring MVC

REST API Integration

Database:

MySQL (to store account and transaction data)

Tools & Environment:

Maven (for dependency management)

Apache Tomcat (embedded with Spring Boot)

IntelliJ IDEA / VS Code / NetBeans

Browser (Chrome, Edge, etc.)

⚙️ How It Works

Enter the Account Number.

Select Transaction Type (Deposit or Withdraw).

Enter the Amount.

Click Submit Transaction.

The system updates:

The ATM Cash Balance dynamically.

The Transaction History Table below.

<h1>📄 Example Flow</h1>
ID	Account Number	Type	Amount	ATM Cash Balance
1	913998238688	WITHDRAW	5000	995000
2	913998238688	DEPOSIT	5001	1000001

<h2>🗂️ Project Structure</h2>
ATM-Transaction-Management/
│
├── src/
│   ├── main/
│   │   ├── java/com/example/atm/
│   │   │   ├── controller/
│   │   │   ├── model/
│   │   │   ├── repository/
│   │   │   ├── service/
│   │   │   └── ATMTransactionManagementApplication.java
│   │   └── resources/
│   │       ├── application.properties
│   │       ├── static/
│   │       └── templates/
│   └── test/
│
├── pom.xml
└── README.md

<h2>⚡ Installation & Setup </h2>

Clone the Repository

git clone https://github.com/<your-username>/ATM-Transaction-Management.git
cd ATM-Transaction-Management


Configure Database

Create a MySQL database named atm_management.

Update your application.properties file:

spring.datasource.url=jdbc:mysql://localhost:3306/atm_management
spring.datasource.username=root
spring.datasource.password=yourpassword
spring.jpa.hibernate.ddl-auto=update


Run the Application

mvn spring-boot:run


Access in Browser

http://localhost:8080

🧑‍💻 Future Enhancements

🔐 Add user authentication for multiple accounts.

🧾 Generate PDF receipts for each transaction.

📈 Include transaction statistics and graphs using Chart.js.

💬 Add real-time notifications for low cash alerts.

📸 Screenshot

<h2>💡 Author </h2>

👨‍💻 Ishwar Deshmukh
📧 [ishwardeshmukh9922@gmail.com]
📍 MCA Student | Java & Spring Boot Developer

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/23eaa1e2-3e2f-4106-bf99-eec157aaee33" />
