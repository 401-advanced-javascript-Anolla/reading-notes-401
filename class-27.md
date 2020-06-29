# React Testing and Deployment

## React Testing
- Snapshots - Make assertions on the exact rendered markup (with content) at any state of the application.
- Render Testing - Similar to snapshots, but allows for jQuery-like inspection of the virtual DOM tree
- Shallow Testing - Executes and renders the called/container component, but does not compose children.
- Mounting - Executes the full component and children. Allows for inspection of rendered Virtual DOM as well as - the current state

## Deployment
- React in development mode uses a node service to create a live website that refreshes as you write code. This is NOT what actually gets deployed when you want your React website to go live. React, remember is an index.html file that uses Javascript to render components in the browser. The node server is only there to aid in your development.

  - npm run build

- This command, executed from the root folder of your React application will output a “static website” containing no more than the index.html, .js and .css files required to open your app.

