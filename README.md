# Address-Book-Management-System-in-C
A CLI-based contact management tool in C with color-coded output and CSV file handling.
📘 Address Book Management System in C

A Command Line Interface (CLI) based project developed in C language to efficiently manage contacts.
This version includes color-coded output for better readability and a more interactive terminal experience.

🚀 Features

➕ Add new contacts

🔍 Search contacts by name or number

✏️ Edit existing contact details

❌ Delete contacts

📃 Display all contacts in a column-wise format

🔁 Detect duplicate entries before saving

🧾 Store and retrieve data using CSV-style File I/O

🌈 Color-coded output for improved user interaction (e.g., success, errors, warnings)

⚙️ Technologies Used

Language: C

Platform: Linux (GCC Compiler)

Concepts Used:

Structures

Arrays & Strings

File Handling

ANSI Escape Codes for Colors

🧱 Project Structure
Address-Book-Management-System-in-C/
│
├── main.c
├── address_book.c
├── address_book.h
├── Makefile
├── contacts.csv          # Data file (auto-created)
└── README.md

📦 How to Run
Step 1: Clone the repository
git clone https://github.com/<your-username>/Address-Book-Management-System-in-C.git
cd Address-Book-Management-System-in-C

Step 2: Compile the project
gcc main.c address_book.c -o address_book

Step 3: Run the program
./address_book

🌈 Sample Output
--------------------------------------------
        ADDRESS BOOK MANAGEMENT SYSTEM
--------------------------------------------

[1] Add Contact
[2] Search Contact
[3] Edit Contact
[4] Delete Contact
[5] Display All Contacts
[6] Exit

Enter your choice: 1
Enter Name: John Doe
Enter Phone: 9876543210
Enter Email: john@gmail.com
✅ Contact saved successfully!



(Colored output will show green for success, red for errors, yellow for warnings, etc.)

🎯 Learning Outcomes

Modular Programming in C

File Handling and Data Persistence

Input Validation & Error Handling

CLI UI Enhancement using ANSI Color Codes

🙌 Acknowledgement

Special thanks to Emertxe Information Technologies for the training and guidance during the development of this project.

📂 GitHub Repository

👉 https://github.com/<your-username>/Address-Book-Management-System-in-C

🏷 Hashtags

#CProgramming #EmbeddedSystems #Project #LinuxCLI #ColorOutput #FileHandling #StudentEngineer #Emertxe
