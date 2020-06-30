# Props and State

- React components can, and often do, have **state**. **State** can be anything, but think of things like whether a user is logged in or not and displaying the correct username based on which account is active. Or an array of blog posts. Or if a modal is open or not and which tab within it is active.
- React components with **state** render UI based on that **state**. When the **state** of components changes, so does the component UI.

- Components accept arbitrary inputs called props. In JSX, **props** are passed into a component with a syntax that looks like HTML attributes. These are the equivalent of function params.
- In actuality, **props** is the name of the object passed into a component constructor and any prop added to a component in the JSX will be accessible as a property on **props**.

- Handling events with React elements is very similar to handling events on DOM elements. There are some syntax differences:
 - React events are named using camelCase, rather than lowercase.
 - With JSX you pass a function as the event handler, rather than a string.