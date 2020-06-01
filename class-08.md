# Express Routing & Connected API

## Routing 
- refers to how an application’s endpoints (URIs) respond to client requests.

### Express 4.0 Router, gives us more flexibility than ever before in defining our routes. we can:

  - Use express.Router() multiple times to define groups of routes
  - Apply the express.Router() to a section of our site using app.use()
  - Use route middleware to process requests
  - Use route middleware to validate parameters using .param()
  - Use app.route() as a shortcut to the Router to define multiple requests on a route


#### Routes can be managed in separate modules from the main server, allowing us to extract that logic and wiring to be more topical.

- How does this change the server’s role?

   - index.js - Entry Point
   - server.js - Hub, Exported Server
   - models/categories.js, etc - Data Models
   - routes/categories.js, etc - Routers and Handlers