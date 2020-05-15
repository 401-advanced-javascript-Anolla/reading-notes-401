# Node Ecosystem, TDD, CI/CD

1. Why would you want to run JavaScript code outside of a browser?
Running JavaScript without/outside a browser means you are using node.js technology to execute your JavaScript code. This type of usage of javascript typically refers to backend programming where your javascript code will interact with your database and can be used to create RESTful APIs.

2. What is the difference between a module and a package?
- A module is a single JavaScript file that has some reasonable functionality.
- A package is a directory with one or more modules inside of it and a package.json file which has metadata about the package.

3. What does the node package manager do?
Node Package Manager (NPM) has a command line tool that installs, updates or uninstalls Node. js packages in your application. It is also an online repository for open-source Node. js packages.

4. Provide code snippets showing 3 different ways to export a function from a node module.
##### Export Function

You can attach an anonymous function to exports object as shown below.
- Log.js
module.exports = function (msg) { 
    console.log(msg);
};

Now, you can use the above module as below.
- app.js
var msg = require('./Log.js');

msg('Hello World');


---------------------------------------------------------------------------------------------------------------
## Vocabulary Terms

- ecosystem :  is a new and rapidly evolving phenomenon in the field of software engineering. It is an approach through which many variables can resolve complex relationships among companies in the software industry.

- Node.js : Node.js is an open source server environment, free, runs on various platforms (Windows, Linux, Unix, Mac OS X, etc.), and it uses JavaScript on the server. Node.js runs single-threaded, non-blocking, asynchronously programming, which is very memory efficient.

- V8 Engine : V8 is Google’s open source high-performance JavaScript and WebAssembly engine, written in C++. It is used in Chrome and in Node.js, among others. It implements ECMAScript and WebAssembly, and runs on Windows 7 or later, macOS 10.12+, and Linux systems that use x64, IA-32, ARM, or MIPS processors. V8 can run standalone, or can be embedded into any C++ application.

- module : A module is any file or directory in the node_modules directory that can be loaded by the Node.js require() function.

- package : bits of reusable code, it's just a directory with one or more files in it that also has a file called package.JSON with some metadata about this package. A package is a file or directory that is described by a package.json file. A package must contain a package.json file in order to be published to the npm registry.

- node package manager (npm): npm makes it easy for js devs to share the code that they have created to solve particular problems and for other devs to reuse that code in their own applications, it's a way to reuse code from other devs and also a way to share your code with them. 

**when we say nmp, we can be talking about one of three things:**

* A website (npm website)

* Registry: a big database of information about packages that people are sharing 

* npm client:which is used when a dev decides to share their code which is installed on their computer to publish this code up to the registry and once there is an entry for this package in the registry then other devs can use their npm clients to install the package from the registry, the entry in the registry for this package is alsi reflected on the website where there is a page dedicated to the new package.

- server : A server is a software or hardware device that accepts and responds to requests made over a network.

- environment : the development environment is the set of processes and programming tools used to create the program or software product.

- interpreter : is a computer program that directly executes instructions written in a programming or scripting language, without requiring them previously to have been compiled into a machine language program.

- compiler : used to convert a program written in a high-level language into machine code(binary code 0's and 1's) understood by computers to create an executable program.