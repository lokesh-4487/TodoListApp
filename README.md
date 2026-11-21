# TodoListApp
# To-Do List Web Application

## About the Project

The To-Do List Web Application is a simple and useful web project that helps users manage their daily tasks. I created this project using HTML, CSS, and JavaScript. The main purpose of this project is to make it easy for users to add tasks, mark completed tasks, and delete tasks when they are no longer needed.

We all have different tasks to complete every day, such as studying, completing assignments, attending meetings, or doing personal work. Sometimes it becomes difficult to remember everything. This To-Do List application provides a simple way to keep track of daily activities in one place.

The application also uses the browser's Local Storage to save tasks. This means that tasks remain saved even after refreshing or reopening the browser.

## Features

The application includes the following features:

- **Add New Tasks:** Users can enter a task in the input box and add it to the list.
- **Mark Tasks as Completed:** Users can click the check icon to mark a task as completed.
- **Delete Tasks:** Users can click the trash icon to remove a task from the list.
- **Save Tasks Automatically:** The application saves task information in browser Local Storage.
- **Restore Saved Tasks:** Previously saved tasks are displayed again when the page is opened.
- **Simple User Interface:** The application has a clean and easy-to-understand design.
- **Task Status:** Completed tasks are displayed with a line-through style so users can easily identify them.

## Technologies Used

I used the following technologies to build this project:

- **HTML5:** Used to create the basic structure of the web application, including the input field and task list.
- **CSS3:** Used to design the application, set colors, manage spacing, and style the task items and icons.
- **JavaScript:** Used to add functionality such as creating tasks, marking tasks as completed, deleting tasks, and saving data.
- **DOM Manipulation:** Used to dynamically create and update task elements on the web page.
- **Browser Local Storage:** Used to store task information in the browser so that data is available after refreshing the page.
- **JSON:** Used to convert task data into a string before saving it and to read the saved data when the application loads.
- **Font Awesome:** Used to display check and trash icons.

## How the Project Works

The working of this application is simple:

1. First, the user opens the To-Do List application in a web browser.
2. An input box is displayed where the user can enter a task.
3. After entering a task, the user presses Enter to add it to the list.
4. JavaScript creates a new list item and displays it on the screen.
5. Every task has a check icon and a trash icon.
6. When the user clicks the check icon, the task is marked as completed.
7. When the user clicks the trash icon, the task is removed from the list.
8. Whenever a task is added, completed, or deleted, the application updates the saved task information in Local Storage.
9. When the page is refreshed, JavaScript reads the saved information and displays the previous tasks again.

## Project Structure

The project contains three main files:

```text
To-Do-List/
│
├── index.html
├── style.css
├── index.js
└── README.md
```

**1. index.html**

This file contains the basic structure of the application. It includes the input field where users enter tasks and an unordered list where tasks are displayed. It also connects the CSS and JavaScript files.

**2. style.css**

This file is responsible for the design of the application. It controls the background color, form layout, input box, task list, text styles, check icon, and delete icon. It also provides a different appearance for completed tasks.

**3. index.js**

This file contains the main functionality of the application. It handles adding new tasks, marking tasks as completed, deleting tasks, and updating Local Storage. It also loads previously saved tasks when the application starts.

## How to Run the Project

Follow these simple steps to run the project on your computer:

1. Download or clone this repository from GitHub.
2. Open the project folder.
3. Make sure all three files (`index.html`, `style.css`, and `index.js`) are present in the same folder.
4. Open the `index.html` file in any modern web browser.
5. The To-Do List application will open and you can start adding your tasks.

No server or database setup is required to run this project.

## Local Storage

One important part of this project is Browser Local Storage.

Local Storage is a feature provided by web browsers that allows websites to save data in the user's browser.

In this project, Local Storage is used to save the tasks entered by the user. JavaScript uses `JSON.stringify()` to convert the task list into a string before saving it. When the application is opened again, `JSON.parse()` reads the saved string and converts it back into JavaScript data.

This helps the application remember tasks even after the browser page is refreshed.

## What I Learned from This Project

While building this project, I learned several important concepts of frontend web development:

- How to create a web page using HTML.
- How to style web elements using CSS.
- How to use JavaScript to make a web page interactive.
- How to select HTML elements using `document.querySelector()`.
- How to create and add new HTML elements using JavaScript.
- How to use event listeners to handle user actions.
- How to use functions to organize JavaScript code.
- How to save and retrieve information using Local Storage.
- How to work with JSON data using `JSON.parse()` and `JSON.stringify()`.
- How to update the user interface dynamically using DOM manipulation.

This project helped me understand how HTML, CSS, and JavaScript work together to create a functional web application.

## Future Improvements

There are some features that can be added to this project in the future:

- Add an option to edit existing tasks.
- Add a feature to clear all completed tasks.
- Add a confirmation message before deleting a task.
- Add task categories such as Personal, Study, and Work.
- Improve the design for mobile and tablet screens.
- Add date and time information for tasks.
- Add a filter to display all, completed, and pending tasks separately.

These improvements can make the application more useful and user-friendly.

## Conclusion

The To-Do List Web Application is a beginner-friendly frontend project that demonstrates the practical use of HTML, CSS, and JavaScript. It provides basic task management functionality and uses Local Storage to keep task information saved in the browser.

Working on this project gave me practical experience with DOM manipulation, event handling, JavaScript functions, JSON, and browser storage. It was a good learning experience and helped me improve my understanding of frontend web development.

**Thank you for checking out my project!**
