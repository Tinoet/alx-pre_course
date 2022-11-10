# Components in react: interactive steps to understanding React.js

-react is a javascript library for building fast and interactive user interface
-developed in 2011 at facebook and also the most popular javascript library for building user interface
how react works:
"COMPONENTS":
-components(functional/class): A piece of user interface e.g, picture a facebook app whose components are the nav, profile, trends and feed sections...
-Therefore building a react app requires building these isolated and reusable components that can be used to build complex user interface.
-think of it as a tree with various branches:
-the tree as the "root component" contains the entire application while the branches  contain other "child components"
What happens in React.js:
-each component as a piece of user interace is brouht together to build a complex user interface*
-the component can then be basically implemented as a javascript class(that has a state and render method)
-the state method deals with the data we want to display when the component is rendered, while 
-the render method is responsible for describing what the user interface should look like.
-the statement further gives an output called a react element(a javascript object that maps with the DOM element) to birth a "virtual DOM"
-Virtual DOM element is a cheap to create(change of state of a component) plain javascript object that keeps a lightweight representation of the DOM. 
-finally React compares the elements with what it has already to figure out what has been changed and updating it on the "real DOM" to keep it in sync with the virtual DOM
Advantages of React.js:
-React unlike vanilla Javascript dont have to work with DOM's API in browser meaning that you no longer have to write codes, equate or manipulate the DOM OR attach event handlers to DOM elements
- with React.js we simply change the state our components and React would automatically update the DOM to match that state. Guess that's why its called React cause when the state changes react essentially updates the DOM to match that state.
Difference between React.js and AngularJavascript:
-Angular javascript is a framework and a complete solution, while
React.js
-React.js is a library that takes care of rendering the view by making sure the view is in sync with the state of the components.
-React offers small trouble in dealing with APIs
You will be forced to use other libraries for things like:
-Routing
-calling HTTP services
and so on...
-But who cares since you have to choose which libraries you prefer to work it unlike Angular JavaScript that has to deal with version breaks.
NB:
-nevertherless they are similar in terms of their component based architecture.
Comment below.
Fun facts: I am learning 🥂