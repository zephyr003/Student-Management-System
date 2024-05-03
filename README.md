# DBMS Student Management System

This is a student management system developed using Python and the tkinter library for the graphical user interface (GUI). The application allows users to manage a database of students, including adding, deleting, and viewing records.

## Features

- **User Authentication**: The application includes a login window for authentication before accessing the main application.
- **Add Records**: Users can add student records with details such as name, email, phone number, gender, date of birth, and stream.
- **Delete Records**: Users can delete individual student records from the database.
- **View Records**: Users can view and select student records to review their details.
- **Reset Fields**: Users can reset input fields to clear data for new entries.
- **Delete Database**: Users can delete the entire student management database if needed.

## Dependencies

- `tkinter` and `ttkthemes`: For the graphical user interface.
- `sqlite3`: For database management and interaction.
- `tkcalendar`: For the date entry widget.

## How to Run

1. Clone this repository to your local machine.
2. Ensure you have Python 3.x installed.
3. Install the required dependencies using the following command:
   ```bash
   pip install tkcalendar ttkthemes
