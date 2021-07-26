# [React lifecycle:](https://medium.com/@joshuablankenshipnola/react-component-lifecycle-events-cb77e670a093)

1- Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?  
 ## render happens first.

2- What is the very first thing to happen in the lifecycle of React?
## *Mounting*, Updating, and Unmounting are the three phases of the component lifecycle.

3- Put the following things in the order that they happen: componentDidMount, render, constructor, , React Updates

### 1-constructor2- render3-componentDidMount4-React Updates
4-componentWillUnmount


4- What does componentDidMount do?
## This method is invoked immediately after a component is mounted. If you need to load anything using a network request or initialize the DOM, it should go here. This method is a good place to set up any subscriptions.