# read02

![state](https://i.stack.imgur.com/wqvF2.png)

## What is a state in React?

What is State? The state is an instance of React Component Class can be defined as an object of a set of observable properties that control the behavior of the component. In other words, the State of a component is an object that holds some information that may change over the lifetime of the component.

## What are props in React?

React allows us to pass information to a Component using something called props (stands for properties). Props are basically kind of global variable or object. We will learn about these in detail in this article. Passing and Accessing props. We can pass props to any component as we declare attributes for any HTML tag.

## Component lifecycle:

We are born, grow, and then die. Almost everything follows this cycle in its life, and React components do as well. Components are created (mounted on the DOM), grow by updating, and then die (unmount on DOM). This is referred to as a component lifecycle.

![LC](https://cdn-media-1.freecodecamp.org/images/1*_drMYY_IEgboMS4RhvC-lQ.png)


1. Mounting:

When an instance of a component is being created and inserted into the DOM it occurs during the mounting phase. Constructor, static getDerivedStateFromProps, render, componentDidMount, and UNSAFE_componentWillMount all occur in this order during mounting.

2. Updating:

Anytime a component is updated or state changes then it is rerendered. These lifecycle events happen during updating in this order.

3. Unmounting:

The final phase of the lifecycle if called when a component is being removed from the DOM. componentWillUnmount is the only lifecycle event during this phase.