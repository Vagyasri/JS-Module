# To Do list: interactive list

## Learning objectives
- Use webpack to bundle JavaScript.
- Learn how to use proper ES6 syntax.
- Use ES6 modules to write modular JavaScript.

### Estimated time: 4h

## Description
In this project, you will add some functionality to your application to make it interactive.  The user will also be able to **mark task completion** by selecting the corresponding checkbox (or undo it by unchecking the checkbox). The updated tasks list will be stored in *local storage*.

*IMPORTANT NOTE: Read **all** requirements before you start building your project.*

### Project requirements

- Add a new JavaScript file and import it as a module:    
    - it will contain methods related to the status updates (`completed`: `true` / `false`).
- Add event listener to the checkbox (`change`).
- Update items object's value for `completed` key upon user actions.
- Implement a function for the "Clear all completed" button (use `filter()` method).
- Store the updated array of items in local storage, so the user gets the correct list values after the page reloads.

## Additional requirements

_These are all optional, but if you're interested in exploring this topic further, feel free to implement them. Any exploration here should be done outside program time._

_If you decide to implement these requirements you should do it in a separate pull request. As always, remember to clearly document your decision in GitHub comments._



The user should be able to reorder the list by **dragging** each item and moving it into the desired position.

- Add a new JavaScript file and import it as a module:    
    - it will contain methods related to drag / drop and sorting functionality.
- Add event listeners to list items (`dragstart`, `dragover`, `drop`).
- Update items object's values for `index` key upon user actions.
