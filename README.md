# React.js Notes
## Component-based Structure

![Component Structure](https://github.com/Niltiwari7/React_js/assets/93751356/0a8b661d-8770-4235-bc5c-e4ee03caffe4)

## Setup

To get started with this project, make sure you have Node.js installed. You can download it from [here](https://nodejs.org/en/download).

## Creating and Nesting Components

In this project, we use a component-based structure. Here's an example of how to create and nest components in React.js:

```jsx
import React from 'react';

function MyButton() {
  return (
    <button>
      I'm a button
    </button>
  );
}

export default function MyApp() {
  return (
    <div>
      <h1>Welcome to my app</h1>
      <MyButton />
    </div>
  );
}
```
## Hello world
```jsx
function App(){
  return(
    <div className="App">
      <h1>Hello  World!</h1>
    </div>
  )
}

export default App;
```

**output**


![image](https://github.com/Niltiwari7/React_js/assets/93751356/01b671d7-186e-439b-842e-08b6bdaae959)

## 1. What are the features of React?
- JSX:  JSX is a syntax extension to JavaScript. It is used with React to describe what the user interface should look like. By using JSX, we can write HTML structures in the same file that contains JavaScript code.
- Components: Components are the building blocks of any React application, and a single app usually consists of multiple components. It splits the user interface into independent, reusable parts that can be processed separately.
- Virtual DOM: React keeps a lightweight representation of the real DOM in the memory, and that is known as the virtual DOM. When the state of an object changes, virtual DOM changes only that object in the real DOM, rather than updating all the objects.

## 2. Can web browsers read JSX directly? 
Web browsers cannot read JSX directly. This is because they are built to only read regular JS objects and JSX is not a regular JavaScript object 
For a web browser to read a JSX file, the file needs to be transformed into a regular JavaScript object. For this, we use Babel.

## 3. What is the virtual DOM?
React keeps a lightweight representation of the real DOM in the memory, and that is known as the virtual DOM. When the state of an object changes, the virtual DOM changes only that object in the real DOM, rather than updating all the objects. 

## 4. Why use React instead of other frameworks, like Angular?
- Easy creation of dynamic applications: React makes it easier to create dynamic web applications because it provides less coding and provides more functionality, whereas, with JavaScript applications, code tends to get complex very quickly.
- Improved performance: React uses virtual DOM, which makes web applications perform faster.
- Reusable components: Components are the building blocks of any React application, and a single app usually consists of multiple components. These components have their own logic and controls, and they can be reused through the application, which, in turn, dramatically reduces the development time of an application.
- Unidirectional data flow: React follows a unidirectional data flow. This means that when designing a React app, we often nest child components within parent components. And since the data flows in a single direction, it becomes easier to debug errors and know where the problem occurs in an application at the moment.

## 5. What is the difference between the ES6 and ES5 standards?
![image](https://github.com/Niltiwari7/React_js/assets/93751356/0c1d1a8f-ab87-4385-bb1c-dd0c6d620401)

## 6. What is an event in React?
An event is an action that a user or system may trigger, such as pressing a key, a mouse click, etc

## 7. What are synthetic events in React?
Synthetic events combine the response of different browser's native events into one API, ensuring that the events are consistent across different browsers.

![image](https://github.com/Niltiwari7/React_js/assets/93751356/cda848db-a53f-4c6f-8c91-929317953b4e)




