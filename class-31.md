# Hooks API

- Hooks are a new addition in React 16.8. They let you use state and other React features without writing a class. A Hook is a special function that lets you “hook into” React features.

- Hooks don’t work inside classes. But you can use them instead of writing classes.

- If you write a function component and realize you need to add some state to it, previously you had to convert it to a class. Now you can use a Hook inside the existing function component

#### Rules to use Hooks:

- Hooks must be named with a use prefix (i.e. useFishingPole)
- Only call Hooks at the top level. Don’t call Hooks inside loops, conditions, or nested functions.
- Only call Hooks from React function components. Don’t call Hooks from regular JavaScript functions. (There is - just one other valid place to call Hooks — your own custom Hooks.
