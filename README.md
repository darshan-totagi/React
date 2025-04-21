The useState hook in React is used to add state variables to functional components.
It takes an initial state value as an argument and returns an array containing the current state and a function to update it. 
This allows functional components to have and manage their own state, similar to how state was managed in class components. 


Key Features:
Uses useState to create a reactive state variable.

Displays the current count to the user.

Increments the count each time the button is clicked.

Explaination:
useState(0): Initializes a state variable count with the value 0.

setCount: A function provided by useState to update the value of count.

handleClick: Function that increments the count by 1 when the button is clicked.

Every time the state changes, React automatically re-renders the component to reflect the updated value.
