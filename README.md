# Fast_React_Pizza_Co.
This project covers some of the fundamentals of building a React application. This includes using components, nesting, props, destructuring, conditional rendering &amp; conditional styling

# Using Components
A component in React is a function that returns JSX. Define a component and use it within a parent component as follows:
<img width="401" alt="image" src="https://github.com/wbdvlpmnt/Fast_React_Pizza_Co./assets/139825457/c7512e53-f3bb-430f-9b3f-ca8a3debceef">

Note a component is designed to be re-used in the application and can be used multiple times. We can combine multiple components, i.e. a header, menu and footer to create a single page application.
<img width="401" alt="image" src="https://github.com/wbdvlpmnt/Fast_React_Pizza_Co./assets/139825457/9156e45d-12fa-4331-af37-dff7cddff796">

We can also use logic inside the component:
<img width="401" alt="image" src="https://github.com/wbdvlpmnt/Fast_React_Pizza_Co./assets/139825457/62d05730-27aa-44f6-8b1f-901962816ec0">

# Styling
We can apply stlyes to HTML elements in a few different ways:
1. Inline Styles
<img width="590" alt="image" src="https://github.com/wbdvlpmnt/Fast_React_Pizza_Co./assets/139825457/f95a88e8-b26a-4736-b077-040ef1bbcdaa">

2. Using a Stylesheet
<img width="249" alt="image" src="https://github.com/wbdvlpmnt/Fast_React_Pizza_Co./assets/139825457/89538a74-3185-49a6-bd61-5ecd03e2a1bd">

# Props
React uses one way data binding. This allows us to pass data as props from a parent component to a child component. An important note about props is that they are immutable. If we want to update the data inside the prop (property) we must update the state in the parent component. 

This is an example of passing props:
<img width="249" alt="image" src="https://github.com/wbdvlpmnt/Fast_React_Pizza_Co./assets/139825457/9d026f0e-cf64-4a04-a34d-8ebbec34248a">

A good practice is to pass the entire object as a prop and use prop destructuring to access the prop keys within the child component:
<img width="249" alt="image" src="https://github.com/wbdvlpmnt/Fast_React_Pizza_Co./assets/139825457/52950524-13c8-446a-9637-86deccc803c7">

# Rendering Lists
We can use the array operator "map" to render lists, this is an example:
<img width="491" alt="image" src="https://github.com/wbdvlpmnt/Fast_React_Pizza_Co./assets/139825457/c5da15bb-0b9c-4e2f-8f4c-efd0f2077614">

Remember to use the correct semantic syntax when rendering lists, specifically ul and li.

# Conditional Rendering
This is an example of conditional rendering with the && operator. This is short circuiting, and only evaluates if the expression is true. A provision for false is not provided:
<img width="618" alt="image" src="https://github.com/wbdvlpmnt/Fast_React_Pizza_Co./assets/139825457/453a9f12-ca67-4677-b0fb-8eb506e017d4">

Another example of conditional rendering is the ternary operator, a provision for false is provided:
<img width="478" alt="image" src="https://github.com/wbdvlpmnt/Fast_React_Pizza_Co./assets/139825457/47e95159-1df3-41e2-b379-d0fe058de0e4">

# Component With 2 Returns:
Useful when you want two different JSX returned from the same component:
<img width="249" alt="image" src="https://github.com/wbdvlpmnt/Fast_React_Pizza_Co./assets/139825457/c0064458-507f-41ba-af02-a8fc502aae93">

# Conditional Styling
This is when you want a style on an element depending on logical conditions:
<img width="502" alt="image" src="https://github.com/wbdvlpmnt/Fast_React_Pizza_Co./assets/139825457/83f48229-1203-4e28-aae5-50c3b85f27bc">







