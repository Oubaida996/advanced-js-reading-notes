# Middleware  
functions are functions that have access to the request object (req), the response object (res), and the next middleware function in the application’s request-response cycle. The next middleware function is commonly denoted by a variable named next.  


## Name 3 real world use cases where you’d want to change the request with custom middleware.  
 
 1. As name suggests it comes in middle of something and that is request and response cycle
2. Middleware has access to request and response object.
3. Middleware has access to next function of request-response life cycle.  


## True or false: The route handler is middleware?

>They are not middleware functions by definition. If such function is used on routing methods then they are only handler functions. We use such a handler function which is not a middleware when it is the only one callback function




## In what ways can a middleware function end the process and send data to the browser?
> Middleware functions can perform the following tasks:

1. Execute any code.
2. Make changes to the request and the response objects.
3. End the request-response cycle.
4. Call the next middleware in the stack.  

1.Which 3 things had you heard about previously and now have better clarity on?  
>I didn't hear about class in jS or Route  

2.Which 3 things are you hoping to learn more about in the upcoming lecture/demo?  
> I am ready to learn everything about classes and router ,middleware.  

3.What are you most excited about trying to implement or see how it works?  
> I am ready to learn everything about classes and router ,middleware.



