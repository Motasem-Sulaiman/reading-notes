## What are the building blocks of a React app?
React apps are made out of components

## What is the difference between an HTML element and a React component?

 React component names must always start with a capital letter, while HTML tags must be lowercase.

## What is JSX and why do we use it?
JSX is stricter than HTML. You have to close tags like <br />. Your component also can’t return multiple JSX tags. You have to wrap them into a shared parent, like a <div>...</div> or an empty <>...</> wrapper

## Describe the process of embedding JavaScript expressions in JSX.

JSX lets you put markup into JavaScript. Curly braces let you “escape back” into JavaScript so that you can embed some variable from your code and display it to the user
You can also “escape into JavaScript” from JSX attributes, but you have to use curly braces instead of quotes. For example, className="avatar" passes the "avatar" string as the CSS class, but src={user.imageUrl} reads the JavaScript user.imageUrl variable value, and then passes that value as the src attribute:
## Does React or JSX have any special features for iteration or conditional logic?
In React, there is no special syntax for writing conditions. Instead, you’ll use the same techniques as you use when writing regular JavaScript code

## How does React know to respond to a user’s inputs?
You can respond to events by declaring event handler functions inside your components:

Notice how onClick={handleClick} has no parentheses at the end! Do not call the event handler function: you only need to pass it down. React will call your event handler when the user clicks the button.

## What word indicates that a React component manages data with a Hook?

Functions starting with use are called Hooks. useState is a built-in Hook provided by React. You can also write your own Hooks by combining the existing ones.


## How can two react components share data?
using props .



## What are the three steps of refreshing a React UI?
Triggering a render , Rendering the component ,Committing to the DOM 
## How do you trigger updates to a component after the initial render?
 it’s done by calling createRoot with the target DOM node, and then calling its render method with your component

## Does React recreate DOM nodes on every rerender?
React only changes the DOM nodes if there’s a difference between renders

## After React has updated the DOM, what still needs to happen before the user sees the change?

After rendering is done and React updated the DOM, the browser will repaint the screen. Although this process is known as “browser rendering”, we’ll refer to it as “painting” to avoid confusion throughout the docs.