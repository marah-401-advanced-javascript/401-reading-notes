# Redux - Combined Reducers
 
 ## Combined Reducers

- is nothing more than pulling in more than one reducer from source and creating a keyed object from them.

- What about the actions?

Each reducer technically has it’s own actions and creators.
However, they can cross over and both be dispatched.
In this example, if an action of type ‘RESET’ is ever dispatched by any action creator, both of the reducers would actually respond.
This can be very powerful, as often times actions are valid for multiple reducers
,but this behavior needs to be well understood or it’ll cause unintended consequences.
 
 ## Using combineReducers

### Core Concepts

- The most common state shape for a Redux app is a plain Javascript object containing "slices" of domain-specific data at each top-level key.

- There are several important ideas to be aware of when using combineReducers:

- First and foremost, combineReducers is simply a utility function to simplify the most common use case when writing Redux reducers.
- While Redux itself is not opinionated about how your state is organized, combineReducers enforces several rules to help users avoid common errors. 
- One frequently asked question is whether Redux "calls all reducers" when dispatching an action. Since there really is only one root reducer function, the default answer is "no, it does not".
- You can use it at all levels of your reducer structure, not just to create the root reducer. It's very common to have multiple combined reducers in various places, which are composed together to create the root reducer.

