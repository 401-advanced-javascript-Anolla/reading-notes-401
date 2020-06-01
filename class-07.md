#  Express

- Express is a routing and middleware web framework that has minimal functionality of its own: An Express application is essentially a series of middleware function calls.

- Middleware functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle. The next middleware function is commonly denoted by a variable named next.


### Express Routing
- Event driven system
app.get('/thing', (req,res) => {})
This is the same pattern we see in Vanilla JS, jQuery
‘When a get event happens in our server, on “/thing”, run this function…’
- The Request Object
  - (req,..)
  - /:parameters
    - app.get('/api/:thing',...) = req.params.thing
  - Query Strings
    - http://server/route?ball=round = req.query.ball
- The Response Object
   - (..., res)
   - Responsible for sending data back to the browser
   - Has methods like send() and status() that Express uses to format the output to the browser properly
     - Sends Headers
      - Cookies
      - Status Codes
  
### Express Middleware
- What does it do?
  - A series of functions that the request “goes through”
  - Each function receives request, response and next as parameters
  - Types of middleware: Application and Route
- Application Middleware
  - Error Handling
  - Bringing in other routes
  - Applies Defaults
  - JSON, Body and Form Parsing
  - Runs on every request
- Route Middleware
  - Dealing with specific things for a route
  - Generally, things many routes would participate in
    - Are you logged in?
    - What is your IP?
    - Have we seen you here before?
- How can we take advantage?
 - Logging
 - Dynamic Model Loading
 - Browser, Location, User specific content
 - Consistent Data Transition/Modeling/Preparation (Pre-Render)

### CRUD Operations with REST and Express
- CREATE
  - app.post('/resource')
- READ
  - app.get('/resource')
- UPDATE
  - app.put('/resource/:id')
- DESTROY
  - app.get('/resource/:id')

