# Purpose and Concept

This code is for a simple task management application that allows users to create, view, and read tasks. It demonstrates key concepts such as:

- Express.js Basics: Handling routes (GET and POST) and serving static files.
- EJS Templating: Rendering dynamic HTML with EJS (index.ejs and show.ejs).
- File System Operations: Using Node.js fs module to create, read, and list files.
- Form Handling: Accepting user input via forms and processing it on the server.

## Installation

You must have [node](https://nodejs.org/en) in your system

- Run the following commands on the terminal over the file's dir

```bash
npm i
npx nodemon
```

Listens on port [4000](localhost:4000)

## Key Concepts:

## Express Middleware:

- app.use(express.json()) and app.use(express.urlencoded({ extended: true })) parse incoming data.
- express.static serves static files.

## Dynamic File Handling:

- Tasks are stored as .txt files, with their names derived from the title.

# EJS:

- <%= %> for embedding variables.
- <% %> for control flow (e.g., loops and conditions).

## File Operations:

- fs.mkdirSync creates directories.
- fs.writeFile saves task details.
- fs.readdir lists tasks.
- fs.readFile reads task content.

## Developed by:

[Sulav Gautam](https://www.instagram.com/gautamsulav000/)

## Preview
![Preview](https://github.com/sulav-gautam/TaskVault/blob/main/previwq.png?raw=true)
