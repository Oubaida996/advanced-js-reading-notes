## Component Lifecycle / useEffect() Hook

##### By using this Hook, you tell React that your component needs to do something after render. React will remember the function you passed (we'll refer to it as our “effect”), and call it later after performing the DOM updates.
![img](https://miro.medium.com/max/5000/1*XcGM-8E_hGl4fpAr9wJIsA.png)  

### Why is useEffect called inside a component?
Each component in React has a lifecycle which you can monitor and manipulate during its three main phases: Mounting, Updating, and Unmounting  
placing useEffect inside the component lets us access the state variable (State of a component is an object that holds some information that may change over the lifetime of the component.and  Hook that allows you to have state variables in functional components , it takes the initial state as an argument and returns an array of two entries. ) right from the effect. We don’t need a special API to read it — it’s already in the function scope. Hooks embrace JavaScript closures and avoid introducing React-specific APIs where JavaScript already provides a solution.