# Task App

This is a simple Task App that allows users to add tasks to a list. The application displays the tasks in a table and uses JavaScript to handle task input and rendering.

## Features
- Users can add a new task to the list using a form.
- The task is displayed in a table with the task name.
- The app dynamically updates the list of tasks using JavaScript.

## Technologies Used
- **HTML**: The structure and layout of the web page.
- **JavaScript**: To add interactivity (task addition) to the page.
- **CSS (optional)**: To style the table and form if desired.

## How it Works
1. The user types a task into the input field and clicks the "Add Task" button (or presses Enter).
2. The JavaScript event listener captures the form submission, prevents the page from refreshing, and gets the value of the task entered by the user.
3. A new table row is created dynamically, containing the entered task, and it is appended to the task list in the table.

## File Structure
```plaintext
.
├── index.html       # The HTML file containing the structure of the Task App
```

## HTML Breakdown
### Structure
- `<table>`: Displays the list of tasks. The tasks are added to the `<tbody>` element with the `id="tasks"`.
- `<form>`: Contains an input field and a submit button. Users can enter a task name in the input field.

### JavaScript
- The script is embedded in the HTML file and listens for the form submission event.
- When the user submits the form, JavaScript prevents the default behavior, retrieves the task value, and adds it to the table.

## Usage
1. Open the `index.html` file in any modern web browser.
2. Enter a task name in the input field.
3. Click the "Add Task" button to see the task added to the list in the table.

## Future Enhancements
- Add the ability to remove tasks.
- Add task categories or priorities.
- Store tasks using local storage so that they persist on page reload.

## License
This project is open-source and free to use. Feel free to modify or enhance it as per your needs!
