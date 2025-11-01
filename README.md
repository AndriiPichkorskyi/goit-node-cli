# Node.js CLI Application — Contacts Manager

## Description

This project implements a **console (CLI) application** for managing a list of contacts.  
The app allows you to list, get, add, and remove contacts stored in a JSON file using Node.js and the **Commander** library.

## Features

- List all contacts in a formatted table
- Get a contact by its ID
- Add a new contact (with name, email, and phone)
- Remove an existing contact by ID

## Technologies

- Node.js (LTS)
- Commander
- fs/promises
- path
- crypto

## Usage

Run the following commands in the terminal:

```bash
# List all contacts
node ./src/index.js -a list

# Get contact by ID
node ./src/index.js -a get -i <contactId>

# Add a new contact
node ./src/index.js -a add -n "Mango" -e "mango@gmail.com" -p "322-22-22"

# Remove a contact
node ./src/index.js -a remove -i <contactId>
```
