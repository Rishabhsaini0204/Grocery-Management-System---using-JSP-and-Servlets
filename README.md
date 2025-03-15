# Grocery-Management-System-using-JSP-and-Servlets
Grocery Management System - using JSP and Servlets + MYSQL DATABASE 


Contact & Support
For queries and support, feel free to reach out:

🌐 Website: [updategadh.com](https://updategadh.com/)

📧 Email: Mail Rishabhsaini0204@gmail.com

📱 WhatsApp: [Chat Now](https://wa.me/917983434684)

📱 Telegram: [Chat Now](https://t.me/rishabhsaini0204)

🔜 Instagram: [Follow Now](https://instagr.am/Rishabhsaini016)

📱 Telegram Group: [Join Now](https://t.me/Projectwithsourcecodes)

📺 YouTube Channel: [Subscribe](https://www.youtube.com/decodeit2/video)


# Grocery Management System using JSP and Servlets

## Introduction
The **Grocery Management System** is a web-based application built using **Java JSP and Servlets** to streamline online grocery shopping. The system enables users to browse and purchase groceries, manage their carts, and receive order confirmations via email. It is designed to enhance user experience through efficient order processing and stock management.

## Features
- User authentication (Registration & Login)
- Product browsing with filtering and search options
- Shopping cart management (Add, remove, update items)
- Secure checkout and payment processing
- Order history and tracking
- Email notifications for registration, order confirmation, and shipment updates
- Admin panel for product and order management

## Technologies Used
### Front-End
- **HTML** – Structure of the web pages
- **CSS** – Styling and responsiveness
- **JavaScript & Bootstrap** – User interactivity and design enhancements

### Back-End
- **Java (JSP & Servlets)** – Server-side functionality
- **JDBC** – Database connectivity
- **MySQL** – Data storage and management
- **Apache Tomcat** – Web server
- **SMTP (JavaMail API)** – Email notifications

## System Requirements
Ensure the following software/tools are installed:
- **Java JDK (v8 or later)**
- **Eclipse IDE (Enterprise Edition)**
- **Apache Tomcat Server (v8.0 or later)**
- **MySQL Database**
- **XAMPP Server**
- **Apache Maven** (for dependency management)

## How to Run the Project
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/Grocery-Management-System.git
   ```
2. **Import the Project into Eclipse**
   - Open **Eclipse IDE**
   - Click on **File > Import > Existing Maven Projects**
   - Browse to the project folder and click **Finish**

3. **Configure the Database**
   - Open **phpMyAdmin (or MySQL Workbench)**
   - Create a new database, e.g., `grocery_store_db`
   - Import the provided SQL file (`database/grocery_store.sql`)

4. **Update Database Credentials**
   - Navigate to `src/config/DbConnection.java`
   - Update the database credentials:
     ```java
     String url = "jdbc:mysql://localhost:3306/grocery_store_db";
     String user = "root";
     String password = "yourpassword";
     ```

5. **Configure Email Settings**
   - Go to **Google Account Security Settings**
   - Enable **2-Step Verification**
   - Generate an **App Password**
   - Update `src/config/MailConfig.java`:
     ```java
     final String EMAIL_USER = "your-email@gmail.com";
     final String EMAIL_PASS = "your-app-password";
     ```

6. **Run the Application**
   - Right-click on the project folder
   - Select **Run As > Run on Server**
   - Choose **Apache Tomcat Server** and click **Finish**
   - Open the browser and visit: `http://localhost:8080/Grocery-Management-System/`

## Default Credentials
### Admin
- **Email:** `admin@gmail.com`
- **Password:** `admin`

### User
- **Email:** `guest@gmail.com`
- **Password:** `guest`


![image](https://github.com/user-attachments/assets/afa7422a-e553-442b-b234-79b9af521987)
![image](https://github.com/user-attachments/assets/3f4121bf-b417-4ebe-b365-2c74606d73ab)
![image](https://github.com/user-attachments/assets/022098cb-4332-453a-af96-7728c81fbeab)




## Project Structure
```
Grocery-Management-System/
│── src/
│   ├── config/              # Database & Email Configuration
│   ├── controllers/         # Servlets for handling requests
│   ├── models/              # Business logic
│   ├── views/               # JSP Pages
│── web/
│   ├── assets/              # CSS, JS, Images
│   ├── WEB-INF/             # Web Configuration
│── database/
│   ├── grocery_store.sql    # Database Schema
│── pom.xml                  # Maven Dependencies
│── README.md                # Documentation
```

## Contributions
Contributions are welcome! Feel free to fork the repository and submit a pull request.

## License
This project is licensed under the MIT License.


---
Made with ❤️ by decodeit

