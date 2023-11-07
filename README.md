# Password-generatr
The Secure Password Generator is a Python project that offers a user-friendly graphical user interface (GUI) for generating strong and secure passwords. This project utilizes various modules and incorporates essential features to create robust passwords based on user-defined criteria while providing error handling through exception handling. The primary modules used are Tkinter for the GUI, the random module for generating random characters, and JSON for configuration settings.
Features:

Tkinter GUI:

The project uses the Tkinter library to create an intuitive and user-friendly GUI.
The GUI includes input fields for users to specify password length, select character types (uppercase letters, lowercase letters, numbers, and special characters), and an option to save or copy the generated password.
A 'Generate Password' button triggers the password generation process when clicked.

Random Password Generation:

The random module is employed to generate passwords.
Users can define the length of the password, allowing for customization based on specific security requirements.
Users can select which character types to include in the generated password (e.g., uppercase letters, lowercase letters, numbers, special characters) to meet specific password complexity guidelines.

Configuration Storage using JSON:

The project utilizes JSON for configuration storage.
Users have the option to save their preferred password settings for future use.
When the program is started, it loads the saved configuration, making it convenient for users who have specific preferences.

Exception Handling:

Exception handling is implemented to ensure the application can gracefully handle errors and unexpected user inputs.
Common exceptions, such as invalid input values or missing configuration files, are caught and displayed to the user in a user-friendly manner.
