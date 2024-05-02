# FullStack Developer Interview

## Table of Contents
- [Javascript](#javascript)
- [Typescript](#typescript)
- [React/NextJs](#reactnextjs)
- [HTML/CSS](#htmlcss)
- [Tailwind CSS](#tailwindcss)
- [T3 Stack](#t3stack)
- [Database](#database)
- [Node/Express](#nodeexpress)
- [Git](#git)
- [Miscellaneous](#miscellaneous)


## Javascript
1. Is JavaScript a single-threaded model or a multi-threaded model?
   - JavaScript is primarily single-threaded. This means that it has one call stack and one memory heap, and code execution is sequential. This single-threaded nature is         often referred to as the "event loop" model, where asynchronous operations are handled through mechanisms like callbacks, promises, and async/await.

   - However, JavaScript can also leverage multi-threading through Web Workers. Web Workers allow developers to run scripts in background threads, separate from the main     
     execution thread. This enables concurrent execution and parallel processing, but it's important to note that these background threads cannot directly access the DOM or       modify the UI, thus preserving the single-threaded nature of the main execution context.

   ##### Simple explanation 
   - Imagine JavaScript as a worker handling tasks. Normally, it's like one person doing one task at a time, just focused on that. But sometimes, with Web Workers, it's like    that person asking some buddies to help with other tasks while they continue with their main job. So, while the main worker stays focused, the helpers tackle additional      tasks, making things more efficient overall.
  
3. Is javascript a compiled or interpreted language?
4. What is call stack in JS?

## Typescript
1. What is the main advantage of using TypeScript over JavaScript in web development?
2. Explain the key differences between a type and an interface in TypeScript.

## React/NextJs
1. What is the key difference between React and Next?
2. When would you choose to use React for a project, and when would you opt for Next.js? Provide specific use cases.
3. What is Cors and why do we need it?

## HTML/CSS
1. Explain the purpose and usage of the HTML <meta> tag.
2. What is the CSS "box model," and how does it impact web layout and design?
3. Can you integrate JavaScript functions into an HTML file for web page interactivity?

## Tailwind CSS
1. What are the main advantages of using Tailwind CSS for styling web applications?
2. You need to add a colour change effect on a button inside a card component but the button should change even colour when the card is hovered over, How would you do that? 

## T3 Stack
1. What is t3 stack?
2. Name some popular technologies that make up the T3 Stack, and briefly describe their roles?

## Database
1. Explain the difference between SQL and NoSQL databases
2. Provide an examples of when to use each type
3. What is normalization? And why is it important

## Node/Express
1. Why was promise converted to async/await? What did it lack and what was fulfilled with the addition?
2. What is the purpose of promise.all()

## Git
1. What is Git?
2. List some commonly used git commands that you use
3. Do you know any complex git commands?
4. What is the role of branches in a collaborative software development project?
5. Explain the role of different types of branches in a typical Git development workflow.

## Miscellaneous
1. Create a function that consoles a value n (user Input) number of times without using built-in function or looping
2. What are web sockets? And what are they used for?
3. what is the difference between a normal REST api and a websocket
4. How would you reverse the order of an array without using a built-in functions  
