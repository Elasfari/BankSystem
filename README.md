# Bank Management System

This is a simple command-line Bank Management System implemented in C++. It allows users to create and manage client accounts, perform transactions, and more. Below are the details of the classes and functionality provided by this program.

## Classes

### `Transaction`
- Represents a bank transaction.
- Attributes: `transactionID`, `transactionName`, `transactionDate`.
- Provides getters and setters for these attributes.
- Allows printing transaction information.

### `Client`
- Represents a bank client.
- Attributes: `clientName`, `clientEmail`, `clientPhone`, `clientAddress`, `clientPassword`, `clientID`, `n`, `ar`.
- Provides getters and setters for client attributes.
- Allows creating transactions, printing client information, and removing transactions.

### `LinkedListNode`
- Represents a node in a linked list containing a `Client` object.
- Attributes: `data`, `next`.
- Provides getters and setters for data and the next node.

### `ClientsLinkedList`
- Represents a linked list of clients.
- Allows adding clients, checking emails, and user login.

## Functions

- `mainMenu()`: Displays the main menu and handles user interactions.
- `loginMenu()`: Handles user login.
- `clientHome()`: Provides options for clients after login.
- `transactionsMenu()`: Allows clients to manage transactions.
- `newClientMenu()`: Allows the creation of new client accounts.
- `forget_password()`: Allows clients to retrieve or change their password.
- `print()`: Prints the list of clients.
- `hashInsert()`: Inserts a client into a hash table.
- `quickSort()`: Sorts linked lists using the Quick Sort algorithm.
- `sortLinkedLists()`: Sorts clients by linked list size.
- `listSize()`: Calculates the size of a linked list.
- `swap()`: Swaps two `LinkedListNode` objects.
- `partition()`: Partitions a linked list for Quick Sort.

## Usage

1. Run the program.
2. Choose from the available options in the main menu to perform various operations.

## Note

- The program simulates a basic bank management system and does not store data permanently. Data is lost when the program exits.
- For security purposes, passwords are not stored in plaintext; they are stored as attributes in the `Client` class.
- The code includes hash table functionality for demonstration purposes.
- It is recommended to replace the use of `rand()` for generating client IDs with a more robust method in a real-world application.

Feel free to use and modify this code as needed for your project or learning purposes.
