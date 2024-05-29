# Employee-Data-Management

## Database Class
### Initialization:
o	Establishes a connection to the SQLite database.
o	Creates a cursor for executing SQL commands.
o	Creates the employees table if it does not exist.
### Insert Function:
o	Inserts a new employee record into the database.
### Fetch Function:
o	Retrieves all employee records from the database.
### Remove Function:
o	Deletes an employee record from the database based on the employee ID.
### Update Function:
o	Updates an existing employee record in the database based on the employee ID.
## Tkinter GUI
### Main Window Setup:
o	Creates the main application window.
o	Sets the title, size, background color, and state of the window.
### Variables:
o	Defines StringVar variables for storing employee details such as name, age, date of joining (DOJ), gender, email, and contact.
### Entries Frame:
o	Creates a frame for input fields.
o	Adds labels and entry widgets for employee details.
o	Adds a combobox for selecting gender.
o	Adds a text widget for entering the address.
### Button Frame:
o	Creates a frame for action buttons.
o	Adds buttons for adding, updating, deleting, and clearing employee details.
### Table Frame:
o	Creates a frame for displaying employee records in a treeview.
o	Configures the treeview style.
o	Sets up columns and headings for the treeview.
o	Binds a function to handle row selection in the treeview.
## Functions
### getData(event):
o	Retrieves data from the selected row in the treeview and populates the input fields.
### displayAll():
o	Clears the treeview and inserts all employee records from the database.
### add_employee():
o	Adds a new employee record to the database and updates the treeview.
### update_employee():
o	Updates the selected employee record in the database and updates the treeview.
### delete_employee():
o	Deletes the selected employee record from the database and updates the treeview.
### clearAll():
o	Clears all input fields in the GUI.
## Main Execution
### dispalyAll():
o	Displays all employee records when the application starts.
### App.mainloop():
o	Starts the Tkinter event loop to run the application.
