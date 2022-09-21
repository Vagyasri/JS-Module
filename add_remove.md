# To Do list: add & remove

## Learning objectives
- Use webpack to bundle JavaScript.
- Learn how to use proper ES6 syntax.
- Use ES6 modules to write modular JavaScript.

### Estimated time: 4h

## Description
In this project, you will implement the CRUD (create, read, update, delete) methods. All the elements of the user interface will be fully functional and your application will be completed. 

*IMPORTANT NOTE: Read **all** requirements before you start building your project.*

### Project requirements
- Remove all hardcoded items from the tasks array.
- Create a new JavaScript file for the new functionality.
- Implement a function for adding a new task (add a new element to the array).
- Implement a function for deleting a task (remove an element from the array).
- Implement a function for editing task descriptions.
- By default new tasks should have the property `completed` set to `false` and the property `index` set to the value of the new array length (i.e. if you're adding a 5th task to the list, the index of that task should equal to 5).
- Deleting a task should update all remaining items' indexes, so they represent the current list order and are unique(i.e. if you're deleting the first task index 1 from the list, the index of the next task(2) should set to 1)..
- All changes to the To Do List should be saved in local storage.
