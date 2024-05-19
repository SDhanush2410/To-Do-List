# To-Do List Web Application

This project is a straightforward To-Do List application designed to help users organize their tasks effectively. The application is built using modern web technologies and follows best practices to ensure a smooth user experience. This is a web application built with Html, CSS and JS.

## Features

- **Add Tasks:** Easily add new tasks using an input field and button.
- **Remove Tasks:** Remove tasks from the list with a single click.
- **Keyboard Support:** Add tasks by pressing the Enter key for a quicker workflow.
- **Dynamic Updates:** The task list updates dynamically without requiring a page refresh.

## Usage Instructions

### Adding a Task

1. Open the web application in your browser.
2. Locate the input field labeled "Add a new task."
3. Type your task into the input field.
4. Click the "Add Task" button or press the Enter key to add the task to the list.
5. Your task will appear in the list below the input field.

### Removing a Task

1. Each task in the list has a "Remove" button next to it.
2. To remove a task, simply click the "Remove" button next to the task you want to delete.
3. The task will be removed from the list immediately.

## Project Structure

The project consists of three main files:

1. **index.html**: This is the main HTML file that structures the web page.
2. **styles.css**: This file contains the CSS rules that define the appearance and layout of the web page.
3. **script.js**: This is the JavaScript file that contains the logic for adding and removing tasks.

### Keyboard Support

An event listener is attached to the input field to listen for the "Enter" key press. When the "Enter" key is pressed, the `addTask` function is called, which follows the same steps as clicking the "Add Task" button.

## Customization

Feel free to customize the project to suit your needs. Here are some ideas:

- **Styling:** Modify `styles.css` to change the appearance of the application.
- **Features:** Add new features such as task editing, task prioritization, or deadlines.
- **Storage:** Implement local storage to save tasks between sessions.
