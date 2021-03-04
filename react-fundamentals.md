### Remember

Answer these on your own, then compare answers as a group

1.  What is React?

React is a Javascript library used to manage the DOM and create front end applications.
-has its own virtual DOM
-uses component based architecture and unidirectional data flow

2.  What is create-react-app?

-A package that sets up a new React project
-Also sets up a developer server that will auto-refresh on changes

3.  What is Component Based Architecture?

-The concept of encapsulating individual pieces of code to bring together into a larger project/app

4.  What is JSX?

A syntax extension to Javascript, it produces React "elements" that show how the UI should appear for that React element.
It is the syntaxt 

5.  What is the virtual DOM?

The virtual DOM is a light-weight copy of the actual DOM.  It is what we will be using to update our user interface in React.

6.  What is unidirectional (one-way) data flow?

This is how React will handle its data meaning that data is passed down from the top of the application to the bottom.  Then use events to send data back up the component tree.

### Understand

Discuss these questions in pairs if you have a 4-person group

7.  Summarize what happens when you run `create-react-app my-app`

Packages and dependencies to install to easily start building

my-app is the name give of your app

8.  Explain what this code does:

```jsx
import React from "react";

const Mentor = props => (
  <div className="mentor-container">
    <h1 className={props.title === "Lead Mentor" ? "lead" : ""}>Tim Biles</h1>
    <ul>
      <li>Fort Worth, TX</li>
      <li>My email address is timbilestimbiles@gmail.com</li>
    </ul>
  </div>
);

export default Mentor;
```

9.  Explain how data is passed from a parent component to a child component.

Only way to pass data from parent to child is through props.

### Apply

Try these on your own, but work together if you start to get stuck.

10.  Use `create-react-app` to create a new React application called `student-directory`

11.  Use the code from `Mentor` above to create a new functional, stateless component called `User` with a list of friends. Hard code the list of friends, do not use state or props.

### Analyze, Evaluate, Create

Discuss these questions as a group

12. What are the benefits and drawbacks of using a tool like create-react-app?

13. Compare and contrast JSX with other templating options, such as those used in Angular or Vue

14. Compare and contrast one-way data flow with two-way data binding.
