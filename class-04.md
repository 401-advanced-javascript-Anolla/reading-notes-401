# Advanced Mongo/Mongoose

- supergoose : Mongoose simple plugin adding some handy functions.

- mongodb-memory-server : Spinning up mongod in memory for fast tests. If you run tests in parallel this lib helps to spin up dedicated mongodb servers for every test file in MacOS, *nix, Windows or CI environments (in most cases with zero-config).

- The Repository Design Pattern : A Repository mediates between the domain and data mapping layers, acting like an in-memory domain object collection. Client objects construct query specifications declaratively and submit them to Repository for satisfaction. Objects can be added to and removed from the Repository, as they can from a simple collection of objects, and the mapping code encapsulated by the Repository will carry out the appropriate operations behind the scenes.

- In-memory database : to use an in-memory MongoDB process to test your mongoose logic without having to create any mocks.