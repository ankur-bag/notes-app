# Notes App (Practice Project)

This is a simple Notes App built with **Node.js, Express, and EJS**.  
Instead of using a database, all notes are stored as plain text files inside a folder, using Node's built-in **fs module**.

## Features
- Create a new note
- View list of notes
- Read note content
- Edit note name
- Delete notes

## Tech Stack
- Node.js
- Express.js
- EJS (Embedded JavaScript Templates)
- TailwindCSS (for styling)
- **fs module** for file storage

## How It Works
- When you create a note, it is saved as a `.txt` file in the `/files` directory.
- The home page lists all existing `.txt` files.
- Clicking **Read More** shows the file contents.
- You can rename or delete files directly from the UI.
- No database is used — everything is handled through the file system.

## Purpose
This project is only for **practicing backend basics**:
- Routing in Express
- Working with EJS templates
- File handling with the Node.js `fs` module
- CRUD operations without a database
