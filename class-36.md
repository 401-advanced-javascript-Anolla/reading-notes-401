# Application State with Redux

- Redux itself is a standalone library that can be used with any UI layer or framework, including React, Angular, Vue, Ember, and vanilla JS. Although Redux and React are commonly used together, they are independent of each other.

- React-Redux is the official Redux UI binding library for React. If you are using Redux and React together, you should also use React-Redux to bind these two libraries.

- The process of subscribing to the store, checking for updated data, and triggering a re-render can be made more generic and reusable. A UI binding library like React-Redux handles the store interaction logic, so you don't have to write that code yourself.

- Overall, React-Redux encourages good React architecture, and implements complex performance optimizations for you. It is also kept up-to-date with the latest API changes from Redux and React.