# Project Name: HBNB (Airbnb Clone)

## Project Description

The HBNB project is a clone of the popular Airbnb platform, created as part of a learning exercise. The project includes the development of a command-line interface (CLI), a dynamic website, a database to manage user reservations, and a RESTful API. The project allows users to interact with the platform through an interpreter to perform actions such as creating, updating, and deleting user profiles and reservations. It provides the foundation for a full-featured web application while focusing on core concepts like object-oriented programming (OOP), database management, and REST API design.

## Command Interpreter

The command interpreter for this project allows users to interact with the application in a command-line environment. Users can perform various operations, such as managing users, reservations, and other entities.

### How to Start the Interpreter

To start the command-line interpreter, navigate to the root directory of the project and run the following command:

```bash
$ ./console.py
```
Once the interpreter is running, you will be presented with a prompt (hbnb) where you can enter commands.

How to Use the Interpreter
help: Displays the list of available commands.
quit: Exits the interpreter.
EOF: Exits the interpreter when provided as input in non-interactive mode.
Example Usage
Starting the Interpreter:

To start the interpreter, simply execute the following command:

```
$ ./console.py
```
Once started, you will see the prompt (hbnb) where you can enter commands.

Get Help:

To view a list of available commands, type help and press enter:

```
(hbnb) help
```
This will display all available commands.

Exit the Interpreter:

To exit the interpreter in interactive mode, type quit or EOF:

bash
Copy code
(hbnb) quit
Or, in non-interactive mode, you can use:

```
$ echo "quit" | ./console.py
```
Installation
To run this project, you will need Python 3.8.5 (or higher) installed along with the necessary dependencies.

Clone the repository:
```
$ git clone https://github.com/your-username/hbnb.git
```
Navigate into the project directory:
```
$ cd hbnb
```
Install required dependencies:
```
$ pip3 install -r requirements.txt
```
Run the command-line interpreter:
```
$ ./console.py
```
Features
Command-Line Interface (CLI): Allows the user to interact with the platform in an interactive or non-interactive mode.
Database: Stores data for users, reservations, and other related entities.
Web Application: A dynamic website built on the foundation of the backend API.
RESTful API: A REST API to enable interaction with external systems or for mobile applications.
Usage Examples
Create a new user:
```
(hbnb) create User
```
Show all users:
```
(hbnb) all User
```
Delete a user:
```
(hbnb) destroy User <user_id>
```
Update a user:
```
(hbnb) update User <user_id> name "User name"
```
Contributors
- Anas Chahid
- Hiba Cherifi
