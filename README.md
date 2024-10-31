1. **Clone the Repository**
You can download the project by cloning the GitHub repository. Open your terminal (or command prompt) and run the following command:
2.**Run the Python Script**
3.**Using the Application**
When prompted, enter your username and password to create an account or log in.
Follow the on-screen instructions to deposit money and manage your bank account.
4.**User Credentials**
The user credentials are stored in a text file named User Credentials.txt. Ensure that this file is in the same directory as your Python script when running the application.
You can manually edit this file to add or modify user credentials.
**Note:** Ensure that the User Credentials.txt file exists before running the application. If the file doesn't exist, the program will start with an empty credentials dictionary.
Feel free to modify the code to add more features or improve functionality!

**Project Overview**
The Bank Account Management System is a command-line application developed in Python that simulates a simple banking system. It allows users to create and manage bank accounts securely by handling user credentials, deposits, and account balance management.

**Features**
User Registration: Users can register by providing a unique username and a secure password. The system checks for existing usernames to prevent duplicates.
Secure Storage of Credentials: User credentials are stored in a text file (User Credentials.txt) in a key-value format, ensuring that the username and password pairs are easily accessible for authentication.
Account Management: Users can deposit money into their accounts. The system maintains an account balance for each user, ensuring that deposits are properly handled and reflected.
Error Handling: The application includes basic error handling to manage incorrect login attempts, ensuring that users receive appropriate feedback.
Command-Line Interface: The system operates through a simple command-line interface, making it easy to use for beginners.
