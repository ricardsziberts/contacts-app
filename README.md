# Contacts app developed with Python

This is a simple contacts management app written in Python programming language.

To develop this app we have used the following programming elements:

- functions
- json module
- file input/output (write/read)


```py
def AddContact():
    name = input("Enter name: ")
    surname = input("Enter surname: ")
    phone = input("Enter phone: ")
    email = input("Enter email: ")

    contact = {
        'name': name,
        'surname': surname,
        'phone': phone,
        'email': email
    }

    contacts.append(contact)```
