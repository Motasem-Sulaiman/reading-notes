## Summarize the five steps of thinking in react.
1: Break the UI into a component hierarchy 
Start by drawing boxes around every component and subcomponent in the mockup and naming them. If you work with a designer, they may have already named these components in their design tool. Ask them!

2: Build a static version in React
To build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props. Props are a way of passing data from parent to child.

3: Find the minimal but complete representation of UI state
Think of state as the minimal set of changing data that your app needs to remember. The most important principle for structuring state is to keep it DRY (Don’t Repeat Yourself).

4: Identify where your state should live 
After identifying your app’s minimal state data, you need to identify which component is responsible for changing this state, or owns the state. Remember: React uses one-way data flow, passing data down the component hierarchy from parent to child component

5: Add inverse data flow
to update the state based on user input.

## What is one reason a local variable isn’t sufficient for managing a React component?
Local variables don’t persist between renders. When React renders this component a second time, it renders it from scratch—it doesn’t consider any changes to the local variables.



## What is the argument to the useState hook, and what are the two parts of its return array?
The state variable (index) with the value you stored.
The state setter function (setIndex) which can update the state variable and trigger React to render the component again.

## How can Component A access state from Component B?
if component B is the parent by sending the state from B to A and access it by props , if its not by using function