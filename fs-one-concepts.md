# Full Stack 1 Assessment

Try your best to answer each question on your own before looking up the answer online. Once you're done writing your first answer, you can google the question and write the best answer you find.

#### 1. What is Enzyme and what are some of the methods that it provides?

Enzyme allows for you to do testimg while using react by making it easier to test your react components output data. It allows for you to manipulate and simulate runtime given the output.


#### 2. What is the difference between dynamic and a static routes?

The main difference between dynamic and static routes are that with dynamic routes you can make variable declaretions with (:) within a route. we can pass anything we like on that section of the URL, and it will be passed to the component as a prop. Static routes are more stagnant. 
 
#### 3. What is a JSON API?

JSON stands for JavaScript Object Notation. It is interchange that can happen between two computer applications at different locatations throughout the world while using the same hardware machine.

#### 4. What is a migration and why would you use one?

A react migration is used whenn you want to update the app without stopping the server from running or rewriting your entire front end. You can migrate the new components to react one small piece at a time.

#### 5. Explain how to set up a route in React.

To set up page routing in react you must first add a new npm package to our app called react-router-com:

yarn add react-router-dom

and in app.js:

import React, { Component } fom "react";
import reactDOM from 'react-dom'
import {
        BrowserRouter as Router,
        Route,
        Link 
} from "react-router-dom";

Routes have a path and a component prop. The path looks for a match in the browsers url and the component prop renders the page when there IS a match.

#### 6. When would you use a generate resource over a generate controller?

- using rails g controller with specific method names causes the generator to only map specific routes to the route file. 
- rails g resources will assume that you want the whole resource functionalilty and will map RESOURCES.


#### 7. Explain the difference between a controller spec and a request spec.

request specs are designed to drive behavior through the full stack including routing

controller specs allow for you to simulate a single http request in each example and then specificy expected outcomes. 

#### 8. Describe the React component lifecycle. What are some of the lifecycle methods?

React lifecycle methods are a series of events tha happen from the birth of a react component to its death common methods include:

- render(): it is the only required method within a class component in react
- componentDidMount(): is called as soon as the component is mounted and ready to go and a good place to initiate API calls
- componentDidUpdate(): A lifecycle method invoked as soon as the updating happens
- componentDidWillUnmount( ): this method is called when the component is unmounted and destroyed. The perfect spot to clean everything up!


#### 9. At this point in the program, what technologies/languages do you find yourself gravitating to?

I find myself gravitating towards react, it's such an abstract language but I feel myself understanding it more and more each day. I want to really master react because it has such a powerful potential.