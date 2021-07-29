
# [React and Forms ](https://reactjs.org/docs/forms.html)

## What is a ‘Controlled Component’?

In HTML, form elements such as input, textarea, and select typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components, and only updated with setState().

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

update the state with their responses as soon as they enter them; it is controlled component , the input’s value is always driven by the React state. While this means you have to type a bit more code, you can now pass the value to other UI elements too, or reset it from other event handlers.

## How do we target what the user is entering if we have an event handler on an input field?
this.state.value
event.target.value 

# The Conditional (Ternary) Operator Explained

## [Why would we use a ternary operator?](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)
 
 to be more organised and professional

### Rewrite the following statement using a ternary statement:

  if(x===y){
 console.log(true);
  } else {
 console.log(false);
  }

  console.log( (x===y) ? 'true' :'false')
