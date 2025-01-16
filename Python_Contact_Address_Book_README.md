# Python Contact Address Book

## Overview
The Python Contact Address Book is a simple yet effective project to manage contacts efficiently. This project demonstrates the use of Python's data handling capabilities and file storage techniques to create a functional contact management system. It allows users to add, view, search, update, and delete contacts from a local address book.

## Features
- **Add Contacts**: Store new contacts with details such as name, phone number, and email.
- **View Contacts**: Display a list of all saved contacts.
- **Search Contacts**: Search for a contact by name or other details.
- **Update Contacts**: Modify existing contact details.
- **Delete Contacts**: Remove unwanted or outdated contacts.
- **File Storage**: Data is stored persistently in a text file for future access.

## Prerequisites
Before running this project, ensure you have the following installed on your system:

- Python 3.x

## Installation
1. Clone this repository or download the ZIP file.
2. Extract the files to your desired directory.
3. Open a terminal and navigate to the project folder.

## Usage
1. Run the Python script using the following command:

   ```bash
   python contact_address_book.py
   ```

2. Follow the on-screen instructions to manage your contacts:
   - Enter your choice from the menu to perform the desired operation.
   - Provide the necessary inputs when prompted.

## Project Structure
- **contact_address_book.py**: The main script containing the functionality for managing contacts.
- **contacts.txt**: A text file used to store contact details persistently (generated automatically after the first run).

## Code Highlights
- **Modular Design**: The code is structured with functions for each operation (add, view, search, update, delete).
- **Error Handling**: Ensures robust input validation and prevents crashes.
- **File Handling**: Uses Python’s built-in file operations to store and retrieve contact information.

## Example
### Adding a Contact
1. Select the option to add a contact.
2. Enter the contact details:
   - Name: John Doe
   - Phone: 1234567890
   - Email: john.doe@example.com
3. The contact will be saved and available for viewing.

### Viewing Contacts
1. Select the option to view contacts.
2. A list of all saved contacts will be displayed.

## Limitations
- Limited to local storage; no database or cloud support.
- No advanced features like grouping or importing/exporting contacts.

## Future Enhancements
- Integrate with a database for better scalability.
- Add GUI support using libraries like Tkinter or PyQt.
- Enable contact grouping and sorting features.
- Support for exporting contacts to CSV or Excel.

## Contributing
Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch.
3. Make your changes and test thoroughly.
4. Submit a pull request.

