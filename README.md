# NativeJS To-Do List

A simple web-based to-do list application built with HTML, CSS, and JavaScript. This application allows users to add, complete, and delete to-do items.

## Features

- Add new to-do items
- Mark items as completed (strikethrough text)
- Delete to-do items

## How to Use

1. **Add a New Item:**
   - Enter your to-do item in the input field.
   - Click the "Add" button to add the item to the list.

2. **Complete an Item:**
   - Click the "Complete" button next to a to-do item to mark it as completed. This will strike through the text.

3. **Delete an Item:**
   - Click the "Delete" button next to a to-do item to remove it from the list.

## Code Explanation

### HTML

- **Structure:**
  - A `div` with the class `todo-container` holds the entire to-do list interface.
  - An `input` field allows users to enter new to-do items.
  - A `button` with the id `addTodoBtn` is used to add new items to the list.
  - An `ul` with the id `todoList` is where the to-do items are displayed.

### CSS

- **Styles:**
  - The body font is set to Arial for a clean look.
  - The `.todo-container` centers the to-do list and adds some padding and border.
  - Each `.todo-item` is styled with a bottom border and some padding for better readability.
  - Completed items are styled with a `line-through` text decoration and a gray color.

### JavaScript

- **Functionality:**
  - Waits for the DOM to fully load before running scripts.
  - Defines `createTodoItem` function to create list items with "Complete" and "Delete" buttons.
  - Adds event listeners to the "Add" button to create and append new items to the list.
  - Adds event listeners to "Complete" and "Delete" buttons to toggle completion status and remove items, respectively.

## Getting Started

To use this to-do list application:

1. Copy the provided HTML code into a new file and save it with a `.html` extension, e.g., `index.html`.
2. Open the file in a web browser.

