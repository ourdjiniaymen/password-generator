# Password Manager

This is a password manager built with Python and SQLite. It allows users to securely store and manage their passwords, as well as generate strong, unique passwords.

## Installation

1. Clone this repository.
2. Install the necessary dependencies with `pip install -r requirements.txt`.
3. Run the `init_db.py` script to initialize the SQLite database.

## Usage

To use the password manager, run `python password_manager.py` from the command line.

### Adding a password

<!-- To add a new password, type `add` at the main menu and follow the prompts to enter the website or app name, the username or email associated with the account, and the password. The password will be encrypted and stored in the SQLite database.
 -->
### Viewing passwords

<!-- To view all stored passwords, type `view` at the main menu. You can also search for a specific password by entering the website or app name.
 -->
### Deleting passwords

<!-- To delete a password, type `delete` at the main menu and follow the prompts to select the password you want to delete.
 -->
## Security
User must provide the correct main password to access the database. The main password is hashed to prevent unauthorized access. The bcrypt hashing algorithm is used to securely store passwords. Before being stored in the SQLite database, passwords are encrypted using the main password as the encryption key. They are decrypted only when the user requests to view them. It is crucial to create strong, unique passwords and avoid reusing passwords across multiple accounts to ensure optimal security.

