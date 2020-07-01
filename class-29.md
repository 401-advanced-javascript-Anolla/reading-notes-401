# Component Composition

- A component can only be in one stage at a time. It starts with mounting and moves onto updating. It stays updating perpetually until it gets removed from the virtual DOM. Then it goes into the unmounting phase and gets removed from the DOM.

- The lifecycle methods allow us to run code at specific points in the component’s life or in response to changes in the component’s life.

- Some components don’t know their children ahead of time. This is especially common for components like Sidebar or Dialog that represent generic “boxes”.

- Such components are recommended to use the special children prop to pass children elements directly into their output