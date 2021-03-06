---
id: 5a24c314108439a4d403614a
title: Moving Forward From Here
challengeType: 6
isRequired: false
---

## Description
<section id='description'>
Congratulations! You finished the lessons on React and Redux. There's one last item worth pointing out before you move on. Typically, you won't write React apps in a code editor like this. This challenge gives you a glimpse of what the syntax looks like if you're working with npm and a file system on your own machine. The code should look similar, except for the use of <code>import</code> statements (these pull in all of the dependencies that have been provided for you in the challenges). The "Managing Packages with npm" section covers npm in more detail.
Finally, writing React and Redux code generally requires some configuration. This can get complicated quickly. If you are interested in experimenting on your own machine, the
<a id='CRA' target ='_blank' href='https://github.com/facebookincubator/create-react-app'>Create React App</a> comes configured and ready to go.
Alternatively, you can enable Babel as a JavaScript Preprocessor in CodePen, add React and ReactDOM as external JavaScript resources, and work there as well.
</section>

## Instructions
<section id='instructions'>
Log the message <code>'Now I know React and Redux!'</code> to the console.
</section>

## Tests
<section id='tests'>

```yml
tests:
  - text: The message <code>Now I know React and Redux!</code> should be logged to the console.
    testString: assert(editor.getValue().includes('console.log("Now I know React and Redux!")') || editor.getValue().includes('console.log(\'Now I know React and Redux!\')'), 'The message <code>Now I know React and Redux!</code> should be logged to the console.');

```

</section>

## Challenge Seed
<section id='challengeSeed'>

<div id='jsx-seed'>

```jsx
// import React from 'react'
// import ReactDOM from 'react-dom'
// import { Provider, connect } from 'react-redux'
// import { createStore, combineReducers, applyMiddleware } from 'redux'
// import thunk from 'redux-thunk'

// import rootReducer from './redux/reducers'
// import App from './components/App'

// const store = createStore(
//   rootReducer,
//   applyMiddleware(thunk)
// );

// ReactDOM.render(
//   <Provider store={store}>
//     <App/>
//   </Provider>,
//   document.getElementById('root')
// );

// change code below this line

```

</div>



</section>

## Solution
<section id='solution'>


```js
console.log('Now I know React and Redux!');
```

</section>
