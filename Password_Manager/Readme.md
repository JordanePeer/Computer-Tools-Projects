# Password Manager App

This is a Python script for a Password Manager program that uses Tkinter library for the graphical user interface (GUI) and sqlite3 for the database.

The program has a root window that displays a label, entry boxes for the user to input data, and buttons for different functions such as saving, updating, 
and deleting records. It also has a treeview widget to display the records and select them.

The db_operation.py file is a separate module that contains a class Operation with methods to interact with the database, such as creating a record, 
updating a record, deleting a record, and showing all records.

The root_window class is the main class that defines the functions for the buttons and treeview, as well as creating the GUI layout. 
The functions for the buttons are save_record, update_record, delete_record, show_records, and copy_password.

Overall, this program allows the user to store and manage passwords for different websites in a simple and user-friendly manner.

First run the code, a GUI interface will pop up:

![image](https://user-images.githubusercontent.com/128277686/226553953-800255ab-148b-4173-b2da-ad21e391ce6f.png)


Then you can insert the information of the choosen password, save it and then it will be displayed in the library:

![image](https://user-images.githubusercontent.com/128277686/226554369-b7b7320f-6fea-412f-8c5b-e66d5d034080.png)


Then from the library you can delete some information by clicking on it in the library,and pressing delete:

![image](https://user-images.githubusercontent.com/128277686/226554693-0851328c-662f-4fff-babb-69908b07cbb2.png)
![image](https://user-images.githubusercontent.com/128277686/226554726-15ce8152-f235-41ad-8687-911a039dc97e.png)


