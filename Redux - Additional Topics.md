## What concerns are addressed by Redux Toolkit?

- Configuring a Redux store is too complicated"
- "I have to add a lot of packages to get Redux to do anything useful"
- "Redux requires too much boilerplate code"

## What does configureStore() do?

wraps createStore to provide simplified configuration options and good defaults. It can automatically combine your slice reducers, adds whatever Redux middleware you supply, includes redux-thunk by default, and enables use of the Redux DevTools Extension.

## How would I use createSlice()?

accepts an object of reducer functions, a slice name, and an initial state value, and automatically generates a slice reducer with corresponding action creators and action types.


## What is Mobx?
MobX is a battle-tested library that makes state management simple and scalable by transparently applying functional reactive programming.

## How does MobX make it “impossible” to produce an inconsistent state?
MobX makes state management simple again by addressing the root issue: it makes it impossible to produce an inconsistent state. The strategy to achieve that is simple: Make sure that everything that can be derived from the application state, will be derived. Automatically.



## How would we build a reactive user interface?
- Identify the parts of your UI that need to be reactive.

- Use MobX to create and manage your application's state, defining observables and actions to update that state.

- React to changes in your observables by using MobX reactions (e.g., autorun or observer).

- Implement user interactions that trigger actions to modify observables.

- Define your UI components to render based on the state stored in MobX observables.

- Test your reactive UI, ensuring that changes to state result in the expected updates to your UI components.

- Optimize performance by using memoization and only updating the UI when necessary.

- Implement error handling and real-time updates as needed.

