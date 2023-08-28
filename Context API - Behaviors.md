## How do useReducer and useContext work together to simplify state management in a React application? (At least two paragraphs of prose.)

Here is how you can combine a reducer with context:

  - Create the context:
   The useReducer Hook returns the current state and the dispatch function that lets you update them,
   To pass them down the tree, you will create two separate contexts:

    TasksContext provides the current list of tasks.
    TasksDispatchContext provides the function that lets components dispatch actions.

 - Put state and dispatch into context:

   Now you can import both contexts in your TaskApp component. Take the tasks and dispatch returned by useReducer() and provide them to the entire tree 

 - Use context anywhere in the tree:

   Now you don’t need to pass the list of tasks or the event handlers down the tree,
   Instead, any component that needs the task list can read it from the TaskContext.
   To update the task list, any component can read the dispatch function from context and call it



