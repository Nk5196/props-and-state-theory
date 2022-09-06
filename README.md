# props-and-state-theory

Q1) what is the difference between Props and State? 
Props-
1) The Data is passed from one component to another.
2) It is Immutable (cannot be modified).
3) Props can be used with state and functional components.
STATE-
1) The Data is passed within the component only.
2) It is Mutable ( can be modified).
3) State is both read and write.

Q2) Explain the useState API? 
Ans - The useState() is a Hook that allows you to have state variables in functional components . 
so basically useState is the ability to encapsulate local state in a functional component.
React has two types of components, one is class components which are ES6 classes that extend from React and the other is functional components.
Class components a Component and can have state and lifecycle methods: class Message extends React.
The  useState hook is a special function that takes the initial state as an argument and returns an array of two entries. 
UseState encapsulate only singular value from the state, for multiple state need to have useState calls.


Q3) Explain the how map, filter, reduce work
Ans - map creates a new array by transforming every element in an array individually.
filter creates a new array by removing elements that don't belong.
reduce , on the other hand, takes all of the elements in an array and reduces them into a single value.
Just like map and filter , reduce is defined on Array.

Q4) 
