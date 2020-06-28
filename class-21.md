# Props and State

### Props

- Components accept arbitrary inputs called props. In JSX, props are passed into a component with a syntax that looks like HTML attributes. These are the equivalent of function params.

- In actuality, props is the name of the object passed into a component constructor and any prop added to a component in the JSX will be accessible as a property on props.

- After props is passed into the constructors super function, they are available on the context by using this.props.

### setState

- `setState()` is the only legitimate way to update state after the initial state setup. Let’s say we have a search component and want to display the search term a user submits.

- We have a search component that displays a search term
- That search term is currently empty
- The user submits a search term
- That term is captured and stored by setState as a value
- Reconciliation takes place and React notices the change in value
- React instructs the search component to update the value and the  search term is merged in

### Handeling Events

- React events are named using camelCase, rather than lowercase.
- With JSX you pass a function as the event handler, rather than a string.
- You must call preventDefault explicitly. 
- When using React, you generally don’t need to call addEventListener to add listeners to a DOM element after it is created. Instead, just provide a listener when the element is initially rendered.