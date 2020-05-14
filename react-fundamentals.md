### Remember

Answer these on your own, then compare answers as a group

1.  What is React?
it is a js library built by facebook to offer seamless one page apps. Used for interfaces and is component based.

2.  What is create-react-app?
it is how you use react to create a new app. It brings in all the tools necessary to build the project.

3.  What is Component Based Architecture?
code is spilt into chunks called components. makes code highly reuseable and easy to debug.

4.  What is JSX?
A JavaScript based language that allows you to create and modify html element objects with familiar html like syntax

5.  What is the virtual DOM?
A virtual copy of the browser DOM stored in memory that React uses to identify and target changes to make in the browser DOM in a process called reconcilliation.

6.  What is unidirectional (one-way) data flow?
data flows down from parent to child

### Understand

Discuss these questions in pairs if you have a 4-person group

7.  Summarize what happens when you run `create-react-app my-app`
when you run it, it brings in the react environtment and tools and creates an app named 'my app'

8.  Summarize the steps for forking and cloning a repo with an existing React app. How does this process differ from the process of creating a new React app on your laptop?
make a directory where you would like to store it in, after you fork and clone, you place it in that directory, you would run npm i to install the depenndencies needed for that react app. 

9.  Explain what this code does:

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

imports react and sets up a functional component that passes in props 

10.  Explain how data is passed from a parent component to a child component.

props

### Apply

Try these on your own, but work together if you start to get stuck.

11.  Use `create-react-app` to create a new React application called `student-directory`

12.  Use the code from `Mentor` above to create a new functional, stateless component called `User` with a list of friends. Hard code the list of friends, do not use state or props.

### Analyze, Evaluate, Create

Discuss these questions as a group

13. What are the benefits and drawbacks of using a tool like create-react-app?

14. Compare and contrast JSX with other templating options, such as those used in Angular or Vue

15. Compare and contrast one-way data flow with two-way data binding.
