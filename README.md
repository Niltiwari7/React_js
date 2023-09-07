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
