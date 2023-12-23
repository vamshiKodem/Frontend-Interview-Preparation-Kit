# Frontend-Interview-Preparation-Kit
>[!NOTE]
>This repo contains complete guidance for Frontend Interview Preparation.


# Clean Code Hack
- Create a meaningful name
- Don’t use words that don’t give much info about variables like date, or variable.
- Don’t use magic numbers assign that to a meaningful name.
- Function name should be small below 20 chars
- For function use a few arguments max of 2. If required use the object
- Don’t repeat yourself
- Don’t leave commented code if not required delete it.
- If using typescript don't compare stings use Types or Enums
- Readability, Reusability, Testability, Modularity
___


# Important HTML Topics
- HTML 5 features
- HTML Document Structure
- Forms (Input types, attributes, validations)
- Semantic tags and uses
- Web Accessibility
- Metatag
- Media tags: image, audio, video
- SEO using HTML tags
- IFrames
---

# Important CSS Topics
- Box Model
- Cascading
- Specificity
- Flex
- Grid
- Selectors
- Pseudo-class Vs Pseudo-elements
- Measurement Units (Absolute vs relative units, Which one to prefer?)
- Positions
- Animations and Transitions
- z-index
- Accessibility
- px vs rem vs vh vs vw
---

# Important Javascript Topics
- Working of JS
  - Execution Context
  - Callstack
- Data types 
 - Primitive type
  - String
  - Boolean
  - Number
  - Symbol
  - Null
  - Undefined
  - Big int
- Non Primitive type
  - Array
    - Map, filter, reduce, splice, slice 
  - Object
    - freeze, seal, isFreeze, isSeal
- Pass by value and pass by reference 
- Array and Object methods
- let/var/const
- Hoisting, Temporal Dead Zone
- Illegal shadowing
- Scope, Scope chaining
- Mutable/Immutable data types
- Shallow and Deep copy
- DOM (DOM methods) and BOM
- Critical Rendering Path
- Functions
  - Function Declaration
  - Function Expression
  - Functional Programming
  - Arrow Functions
  - IIFE
- this keyword
- Call, Apply, Bind
- Closure and its uses
- Callbacks, Callback Hell
- Promises, promise chaining
  - Promise.all()
  - Promise.allSettled()
  - Promise.any()
  - Promise.race() 
- Async/Await
- Currying
- Debouncing and Throttling
- Event Propagation
  - Bubbling
  - Capturing
  - Event Delegation
- Prototype and Prototypal Inheritance
- Memoisation
- Map and Set
- Generator Functions
- Working on JS Engine
- Event Loop, Mictrotasks,
- Events: DOMContentLoaded, load, beforeunload, unload
- async/defer
- Polyfills (Mostly asked polyfills: Promise, Promise.all, Promise.any, Promise.race, Promise.allSettled, call, apply, bind, map, reduce, filter, forEach, flat, fetch API)
- Web APIs
- setTimout, setInterval
- High Order Functions
- JS Engine
- <a href="https://javascriptpatterns.vercel.app/patterns">Important link for design pattern (Js and React)</a>
___

# Practice Time!
Remember practice makes a man perfect. So, here we will focus on practicing conceptual questions and making basic applications in JS.

Practice on the following links step by step:

<p><a href='https://leetcode.com/studyplan/30-days-of-javascript/'>Leetcode 30 days of JS</a></p>
<p>Start with Easy questions, then Medium and Hard: GreatFrontend JS Problems: Solutions</p>
<p><a href='https://bigfrontend.dev/'>BigFrontEnd Javascript Problems</a></p>
  
Above mentioned resources are more than enough for practicing Javascript questions. Now comes the turn of practicing by making some small applications in HTML, CSS, JS. Such type of questions are generally asked in Machine Coding rounds.

Adding below a list of small applications that you can practice:

- Star Rating
- Implementing Flipkart Search bar functionality using debouncing or throttle
- Typeahead/ autocomplete search bar
- Todo List (Having CRUD operations)
- Creating components like Carousel, Accordion, Popover
- Infinite Scroll
- Implement tic-tac-toe
- Create Images gallery(Use optimations like infinite scroll, pagination, and search functionality)
- Implement a poll widget
- Implement an Event Emitter
- Implement a Kanban board having tasks and subtasks
- Creating a basic Chat Application
- Implement Comment Widget (add comments, add multiple replies to comments, and delete them like Facebook or Instagram)
- Food Ordering App having Search, Sort, Filter, Add to Cart Functionality
- Build a calculator (add/subtract... then multiply/divide... then log/pow... etc)
- Create a progress bar having start/restart, pause, and stop functionality
- Create an Analog Clock
- Implement Day Calendar
- Create a Todo List using Drag and Drop
___

# Web Fundamentals!

- Web Performance and Optimisations
  - Lazy Loading
  - Code splitting
  - Caching the services
- Web Vitals
  - Largest contentful paint
    - Oversize files
    - Bad hosting
    - Uncompressed images 
  - First input delay
  - cumulative layout shift 
- Storing Data in the browser
  - Local storage
  - Session storage
  - Cookie 
- Network requests
- DOM
- Security
  - SSL Pinning
  - Security Vunarablitites
    - Cross-site scripting (XSS)
    - Cross-site Request Forgery (CSRF)
    - SQL Injection (SQL I)  
- Design Patterns 
- Other Important Topics
___


# Frontend System Design!

Listing some best resources for studying System Design in Frontend, go on and binge-watch them:

- <p><a href="https://www.youtube.com/watch?v=5vyKhm2NTfw&list=PLI9W87-Dqn7j_x6QtR6sUjycJR7nQLBqT">Front-End Engineer YT Channel</a></p> 
- <p><a href='https://www.youtube.com/watch?v=sV_4pOGosnU&list=PL4CFloQ4GGWICE0Tz6iXKfN3XWkXRlboU'>Chirag Goel YT Channel</a></p>
- <p><a href='https://bigfrontend.dev/design'> BigFrontend Frontend Design Questions</a></p>
- <p><a href="https://www.greatfrontend.com/system-design">GreatFrontend Design Questions</a></p> 

The above resources will help you in understanding the way you can deal with System Design rounds, although these solutions are not the only ones, you can come up with your own ideas as well. Also, different interviewers have different expectations when they ask you to provide a design for any system, no solution is the best/concrete solution in that case, however you can follow this pattern for framing your answers:

GreatFrontend System Design Framework

---

# Important React Topics

- Hooks
  - useState()
  - useEffect()
  - useCallback()
  - useMemo()
  - useRef()
  - useReducer()
  - useContext()
  - useId()
  - useLayoutEffect() (useLayoutEffect can hurt performance. Prefer useEffect when possible.)
- How does react work under the hood
  - React reconciliation
  - diffing algorithm
  - JSX (What happens to jsx when we run react)
  - React keys (Why we should not use the index as a key for the list where we can modify the list)
  - Virtual dom
  - React Fiber
- React Lifecycle methods (Class and Functional)
- How React update the async updates
- State management (Context, Redux)
- React with typescript
- props and props drilling
- Difference between class components vs functional components
- Webpack (about Webpack and its uses)
- Performance optimization
  - Add only optimized images and cache the images locally
  - Avoid unnecessary component rerendering by using useCallback, useMemo for expensive calculations and memoizing the component.
  - Lazy loading of Images
  - Lazy loading and Code spitting
  - Keep state as local as possible to component.
  - Optimize the state (In react rerendering happens when state changes). 
- React Design Patterns (<a href="https://blog.logrocket.com/react-design-patterns">Useful link</a>,  <a href="https://javascriptpatterns.vercel.app/patterns">Js and React</a>)
  - Container/Presentational Pattern (We can use the Container/Presentational pattern to separate the logic of a component from the view)
  - Higher-Order Components (Pass reusable logic down as props to components throughout your application)
  - Render Props Pattern (Pass JSX elements to components through props)
  - Hooks Pattern (Use functions to reuse stateful logic among multiple components throughout the app)
  - Provider Pattern (Make data available to multiple child components)
  - Compound Pattern (Create multiple components that work together to perform a single task)
- Redux
  - Single source of truth: The global state of our application is always put away in an object tree inside one store.
  - The state is read-only: The only way to change the state of our application is by emitting an action, an object explaining what has happened.
  - Changes are made with pure functions: This principle means that in order to define how the state tree is being transformed by the actions, we have to write pure reducers.
- Architecture
  - Monolithic
  - Micro frontend
  - Monorepo
- Unit testing
- Routing, Dynamic Routing, Secure Routing and public Routing

___  

# Important React Native Topics
- Hooks
- React Native threads (Main thread, javascript thread)
- Bridge
- Performance issue (The real cause behind React Native performance issues is that each thread (i.e. Native and JS thread) is blazingly fast. The performance bottleneck in the React Native app occurs when you’re passing the components from one thread to another unnecessarily or more than required)
- Build process
- How React Native work under the hood
- Optimizing the React Native Apps
  - Using a Flat list or Section list instead of a scroll view for a large list of items. So they uses lazy loading internally.
  - Minimizing the interaction between the UI thread and the main thread
  - Caching the services and images
  - Adding only optimized images or svg's
  - Use of useCallback and useMemo for expensive things
  - Memozie the expensive calculation.
  - Minimize the rerender.
  - Optimized state management.
