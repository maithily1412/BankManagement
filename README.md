Name: Maithily Vyas
Company: CodTech IT solutions 
Code: CT04JP2168 
Domain: Java Programming 
Mentor: Sravani gouni
Bank Management System
Overview
The Bank Management System is a Java-based application designed to simulate common banking transactions such as deposits, withdrawals, balance inquiries, fast cash withdrawals, mini-statements, and PIN changes. The application features a graphical user interface (GUI) built using Swing, providing an interactive and user-friendly experience.

Features
Deposit: Allows users to deposit a specified amount into their account.
Withdrawal: Enables users to withdraw a specified amount from their account.
Balance Inquiry: Displays the current balance of the user's account.
Fast Cash: Provides options for quick cash withdrawals of predefined amounts.
PIN Change: Allows users to change their account PIN.
Mini Statement: Displays a mini statement of recent transactions.
Exit: Allows users to exit the application.

Project Structure

project-root/
├─ src/
│   └─ bank/
│       └─ management/
│           └─ system/
│               ├─ MainClass.java
│               ├─ Deposit.java
│               ├─ Withdrawal.java
│               ├─ BalanceEnquiry.java
│               ├─ FastCash.java
│               ├─ PinChange.java
│               └─ MiniStatement.java
└─ resources/
    └─ icon/
        └─ atm2.png
Getting Started
Prerequisites
Java Development Kit (JDK) installed.
IntelliJ IDEA or any other Java IDE installed.
Installation
Clone the repository:


git clone https://github.com/yourusername/bank-management-system.git
Open the project in IntelliJ IDEA:

Open IntelliJ IDEA.
Select Open or Import.
Navigate to the cloned repository and select it.
Click OK.
Set up resources:

Ensure that the resources directory is marked as a Resources Root:
Right-click the resources directory.
Select Mark Directory as -> Resources Root.
Running the Application
Run Configuration:

Create a run configuration for the MainClass:
Click on the dropdown in the top-right corner and select Edit Configurations.
Click the + icon and select Application.
Set the Main class to bank.management.system.MainClass.
Apply the changes and close the dialog.
Run the Project:

Click the Run button (green triangle) to start the application.
Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

License
This project is licensed under the MIT License - see the LICENSE file for details.
