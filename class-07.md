## EXPRESS

### Express Routing:

1- Event driven system

2- The Request Object

3- The Response Object

### Express Middleware:

- a series of functions that the `request` goes through.
- Each function receives `request`, `response` and `next` as parameters

- **Application Middleware**:
- Error Handling
- Bringing in other routes
- Applies Defaults
- JSON, Body and Form Parsing
- Runs on every request


- **Route Middleware**:
- Dealing with specific things for a route
- logging
- IP

### CRUD Operations with REST and Express

- CREATE :`app.post('/resource')`
- READ :`app.get('/resource')`
- UPDATE :`app.put('/resource/:id')`
- DESTROY :`app.get('/resource/:id')`

### Server Testing :

- `supertest` to run your tests,This will hit your routes as though your server was running, without actually starting it. 
- `superagent` this allows you set up a “mock” of this new agent module
-  folder called `__mocks__` where the agent.js file is with an agent.js file in it
