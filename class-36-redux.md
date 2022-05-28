# Application State with Redux

>Redux allows you to manage your app's state in a single place and keep changes in your app more predictable and traceable. It makes it easier to reason about changes occurring in your app. But all of these benefits come with tradeoffs and constraints.

![img](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTPF6YvOv2dE6oGUWaCSuTQeliy6ilNYducoA&usqp=CAU)

![img](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSE8MjLKG64PNz-jb3wghnUCaUbAFI1MqxDEw&usqp=CAU)


## Integrating Redux with a UI framework  

Using Redux with any UI layer requires the same consistent set of steps:  


- Create a Redux store
- Subscribe to updates
- Inside the subscription callback:
    - Get the current store state
    - Extract the data needed by this piece of UI
    - Update the UI with the data  

- If necessary, render the UI with initial state
- Respond to UI inputs by dispatching Redux actions  

The process of subscribing to the store, checking for updated data, and triggering a re-render can be made more generic and reusable. A UI binding library like React Redux handles the store interaction logic, so you don't have to write that code yourself.
