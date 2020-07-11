## Redux

Managing state with Redux requires the combination of 3 distinct aspects into a “Store” which all components can access as they please.

- State
- Reducers (strategies to alter state)
- Actions (methods that get “dispatched” or “run”, which trigger associated reducers)


## Redux Store
- Ultimately, the “store” is where your application state is, well, stored. The store’s job is to identify the various reducers and middleware that need to be made available and used globally.

- React uses “reducers” to hold and manage state. Reducers typically manage just one part of the larger application state. For example, in a storefront application, you would likely have a separate reducer for Products, Categories, and Carts

- React applications with Redux dispatch “actions” (like an event) with “payload” (data). An action creator function as shown below always returns an action object with the action type to perform and the data to perform it with. When your component wants to modify state, it “Dispatches” (calls) an action and sends whatever payload (data) it needs to, to the reducer.