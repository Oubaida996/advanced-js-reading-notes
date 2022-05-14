# Context API

### The Context API is a React structure that enables you to exchange unique details and assists in solving prop-drilling from all levels of your application.  

Context provides a way to pass data through the component tree without having to pass props down manually at every level.

In a typical React application, data is passed top-down (parent to child) via props, but such usage can be cumbersome for certain types of props (e.g. locale preference, UI theme) that are required by many components within an application. Context provides a way to share values like these between components without having to explicitly pass a prop through every level of the tree.

![img](https://uploads.toptal.io/blog/image/129071/toptal-blog-image-1549323314875-d6bc9c753a4c9ac2911e8af17732023d.png)


### When to Use Context?

***  
Context is designed to share data that can be considered “global” for a tree of React components, such as the current authenticated user, theme, or preferred language.
*** 



