# Todo App

## Overview
This Todo App is a simple web application that allows users to create a list of tasks with due dates. Users can add and delete tasks as needed. The project demonstrates the use of HTML, CSS, and JavaScript to create a functional and interactive user interface.

## Files

- **index.html**: The main HTML file that contains the structure of the app.
- **todo.css**: The CSS file that styles the app, including the layout, colors, and other visual elements.
- **todo.js**: The JavaScript file that handles the app's functionality, such as adding and deleting tasks.

## Features
- **Add Todo**: Users can add a task along with a due date.
- **Delete Todo**: Users can delete a task from the list.

## Structure

### HTML (`index.html`)
- The main heading `<h1>` with the text "Todo App".
- A container with a grid layout (`grid-container`) for the input field, date picker, and "Add" button.
- A container (`todo-container`) that displays the list of tasks.

### CSS (`todo.css`)
- **Body**: Set to a flex layout with a column direction, centered items, and a light background color.
- **Main Heading**: Centered text with a large font size and a dark color.
- **Grid Container**: A grid layout with three columns for the input field, date picker, and "Add" button.
- **Todo Container**: A styled container with a white background, rounded corners, and a shadow effect, containing the list of tasks.

### JavaScript (`todo.js`)
- **addTodo**: A function that adds a new task to the `todoList` array and refreshes the display.
- **displayItems**: A function that displays the tasks from the `todoList` array in the HTML.

## Usage

1. **Adding a Todo**:
   - Enter a task in the "Enter Todo here" input field.
   - Select a due date using the date picker.
   - Click the "Add" button to add the task to the list.

2. **Deleting a Todo**:
   - Click the "Delete" button next to a task to remove it from the list.

## Future Enhancements

- Implementing a backend to persist the todos.
- Adding user authentication.
- Adding features like editing tasks, setting task priorities, and sorting tasks.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- This project is inspired by basic todo applications and tutorials available online.