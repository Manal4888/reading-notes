# REACT Putting it all together

## ## How would you break a mock into a component heirarchy?
Using single responsibility principle,
but first  you will need to draw boxes around every component (and subcomponent) in the mock and give them all names

## What is the single responsibility principle and how does it apply to components?

is a technique to know what should be its own componentt.

## What does it mean to build a ‘static’ version of your application?
To build a static version of your app that renders your data model, you’ll want to build components that reuse other components and pass data using props. props are a way of passing data from parent to child. If you’re familiar with the concept of state, don’t use state at all to build this static version. State is reserved only for interactivity, that is, data that changes over time. Since this is a static version of the app, you don’t need it.

## Once you have a static application, what do you need to add?
to Figure out the absolute minimal representation of the state your application needs and compute everything else you need on-demand

## What are the three questions you can ask to determine if something is state?
Is it passed in from a parent via props? If so, it probably isn’t state.

Does it remain unchanged over time? If so, it probably isn’t state.

Can you compute it based on any other state or props in your component? If so, it isn’t state.

## How can you identify where state needs to live?
we need to identify which component mutates, or owns, this state.