## What is the first principle of Redux?

Single source of truth: This means that the entire state of an application is stored in a single JavaScript object called the "store." This makes it easier to manage and track changes in the application's state.

## what is a store and what do we use our reducers for within that store?
Store: The store is a fundamental concept in Redux. It is a plain JavaScript object that holds the entire state of your application.


Reducers: Reducers in Redux are functions responsible for specifying how the state of the store should change in response to actions. They take in the current state and an action as parameters and return a new state


## Name three Redux store methods given to us by createStore and describe their use.


- getState():
to retrieve the current state of the Redux store. It returns the current state object, which represents the entire state tree of your application. This method is read-only and does not modify the state.


- dispatch(action): to dispatch an action to the Redux store. Actions are objects that describe what should happen in your application, and they are used to trigger state changes. 


 
- subscribe(listener): is used to subscribe a listener function to the Redux store. The listener is called whenever an action is dispatched and the state is potentially updated. This allows your application to react to state changes and update the user interface accordingly. 


## Explain to a non-technical recruiter what combineReducers() does and why it is useful.

combineReducers() is a helpful tool in Redux that takes care of organizing and connecting the different pieces of your application's data. It keeps your code tidy, modular, and scalable, making it easier to manage and maintain, just like how you'd want to organize and assemble puzzle pieces to complete a beautiful picture.