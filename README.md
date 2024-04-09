Task Management Site

This is a simple task management site built using an Immediately Invoked Function Expression (IIFE). It allows users to add tasks, mark them as completed, and remove them from the list.
Features

    Add Tasks: Enter a task in the input field and press enter or click submit to add it to the list.
    Mark as Completed: Click on a task to mark it as completed. The task will be visually crossed out.
    Remove Tasks: Click on a task to remove it from the list.

Usage

    Clone or download this repository to your local machine.
    Open index.html in your web browser.
    Use the input field to add tasks by typing and pressing enter or clicking submit.
    Click on a task to mark it as completed or to remove it from the list.

Implementation Details

This task management site is implemented using HTML, CSS, and vanilla JavaScript. It utilizes an IIFE (Immediately Invoked Function Expression) to encapsulate the code and keep the global scope clean.
State Variables

    toDoListArray: An array that stores the tasks added by the user.

Variables

    form: Reference to the HTML form element for adding tasks.
    input: Reference to the input field for entering task text.
    ul: Reference to the unordered list where tasks are displayed.

Event Listeners

    submit: Listens for form submission to add a new task.
    click: Listens for clicks on the list items to mark them as completed or remove them.

Functions

    addItemToDOM(itemId, toDoItem): Creates a new list item and adds it to the DOM.
    addItemToArray(itemId, toDoItem): Adds the task to the toDoListArray.
    removeItemFromDOM(id): Removes the specified list item from the DOM.
    removeItemFromArray(id): Removes the specified task from the toDoListArray.

Contributors

    Kelvin Ng'Ola Mutuku ==> Fourty

Feel free to contribute to this project by submitting pull requests or opening issues. If you have any suggestions or feedback, please let us know!
