# Simple Contact Manager 

> Simple project for contact manager using Java language.

## How to run? 

``` bash
javac ContactManagerApp.java
java ContactManagerApp
``` 
**Contact Class**
Represents a single contact with the following attributes and methods:

- `Attributes`:
  
`name`: The name of the contact.

`phoneNumber`: The phone number of the contact.

- `Methods`:
  
`Contact`(String name, String phoneNumber): Constructor to initialize the contact.

`getName`(): Returns the name of the contact.

`getPhoneNumber()`: Returns the phone number of the contact.

`toString()`: Returns a string representation of the contact.

**ContactManager Class**

Manages a list of contacts with the following methods:

- `Attributes`:
  
`contacts`: An ArrayList that stores Contact objects.

- `Methods`:
  
`ContactManager()`: Constructor to initialize the contact list.

`addContact(String name, String phoneNumber)`: Adds a new contact to the list.

`viewContacts()`: Displays all contacts in the list.

`deleteContact(String name)`: Deletes a contact by name from the list.

**ContactManagerApp Class**

Contains the `main` method to run the application. It provides a menu for user interaction:

