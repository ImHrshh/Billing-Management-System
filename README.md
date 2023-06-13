# Billing-Management-System
This is a C++ program for a billing management system. It allows users to input item details, such as name, quantity, and price, and calculates the total price including VAT (Value Added Tax). The program also maintains a history of previous entries and provides options to view the history or enter a new entry.

The program consists of several classes: head, vat, and the main class. The head class handles input and output of item details, while the vat class extends the head class and adds VAT calculation functionality. The main class controls the flow of the program and includes a password protection feature.

The program starts by prompting the user for a password. If the correct password is entered, the user is presented with a menu to either enter a new entry, view previous entries, or exit the program. When entering a new entry, the user can input item details, and the program calculates the total price with VAT. The history of entries is stored in a file called "History.TXT" and can be viewed by selecting the appropriate option from the menu.

The program utilizes various file handling functions for input and output operations, such as reading from and writing to files.

Please note that the effectiveness and completeness of the code cannot be guaranteed without further analysis, and it may require additional modifications to be fully functional or meet specific requirements.
