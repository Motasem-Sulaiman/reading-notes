## What is the motivation for adding a reducer?
Components with many state updates spread across many event handlers can get overwhelming. For these cases, you can consolidate all the state update logic outside your component in a single function, called a reducer


##   What are actions in the context of a reducer? How are they different than setting state directly?
Managing state with reducers is slightly different from directly setting state. Instead of telling React “what to do” by setting state, you specify “what the user just did” by dispatching “actions” from your event handlers. (The state update logic will live elsewhere!) So instead of “setting states” via an event handler, you’re dispatching some actions. This is more descriptive of the user’s intent.

## What common list operation is useReduce named for, and why?
reducers can “reduce” the amount of code inside your component, they are actually named after the reduce() operation that you can perform on arrays.

The reduce() operation lets you take an array and “accumulate” a single value out of many

## When should you switch from useState to useReducer?
if you have many states with complex logic you should switch from useState to useReducer