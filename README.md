# To-Do List App

A simple To-Do List application built with HTML, CSS, and JavaScript. This project demonstrates the usage of **localStorage** to save, retrieve, and delete tasks, even after refreshing the browser.

## Features

- **Add new tasks**: Enter a task and save it to the to-do list.
- **Delete tasks**: Remove individual tasks from both the list and local storage.
- **Persistent storage**: All tasks are saved in `localStorage`, so they stay even after refreshing or closing the app.
- **Automatic loading**: When the app starts, tasks are loaded from `localStorage` and displayed in the list.

## Purpose

This project highlights basic web development skills and the use of `localStorage` for data persistence in JavaScript.

## Usage

1. **Add a Task**: Type a task in the input area and click **Add** to save it to the list.
2. **Delete a Task**: Click the **Delete** button next to a task to remove it from both the list and `localStorage`.
3. **Stable Tasks**: Tasks are stored in `localStorage`, so they will reappear in the list upon reloading the page.

## Functions

- `saveNote()`: Saves the content of the text input as a new task in `localStorage` and displays it on the page.
- `deleteNote()`: Removes a specific task from both `localStorage` and the display.
- `createNote()`: Creates a new HTML element for a task, including a delete button, and adds it to the list of tasks on the page.
- `init()`: Loads all saved tasks from `localStorage` when the app starts and displays them.

## Technologies Used

- **HTML** for structure
- **CSS** for basic styling
- **JAVASCRIPT** for functionality and `localStorage` integration

## Setup

1. Clone or download the repository.
2. Open index.html in your browser to launch the application.

## Contact

If you have any questions, suggestions, or feedback, feel free to text me!
