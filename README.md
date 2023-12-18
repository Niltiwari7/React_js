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
