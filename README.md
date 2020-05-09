React.js

React is an efficient and flexible front-end JavaScript library for building user interfaces. It lets us build complex UIs from small bits of code called Components that can be reused.

Components are the building blocks of React. Every component in react has a render method which describes the UI for the component. ReactDOM.render() method takes in two arguments, the first argument is the component that we want to render and the second argument is the DOM node where we want to render the component.

React uses virtual DOM. React components has a built-in state object which stores the properties of a component. When the state of a component changes, React updates the virtual DOM tree. Once the virtual DOM has been updated, React then compares the current version of the virtual DOM with the previous version of the virtual DOM and updates only those objects that have changed, in the real DOM.

The Todolist App

I have made this simple Todolist application using React. When we type in a task in the input form and click Add Todo button or hit enter, the task appears as an entry. We can add as many tasks as we require. To remove an item we need to click on that existing entry and that entry or task will be removed.

The two components that i have used to build this project are:

TodoList - This basically does the job of adding a task and deleting tasks from the list.
TodoItems - This serves the purpose of displaying the tasks in the screen as list items.

