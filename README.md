# Frontend Interview Preparation Kit

> [!NOTE]
> This repo contains complete guidance for Frontend Interview Preparation.

---

## Clean Code Hack

- Create a meaningful name.
- Don’t use vague variable names like `date` or `variable`.
- Don’t use magic numbers; assign them to meaningful constants.
- Function names should be short (below 20 characters).
- Limit function arguments to max 2; if more, use an object.
- Don’t repeat yourself (DRY).
- Remove commented-out code if not needed.
- In TypeScript, use Types or Enums instead of string comparisons.
- Four pillars of coding: **Readability, Reusability, Testability, Modularity**.

---

## Important HTML Topics

- HTML5 features
- HTML Document Structure
- Forms (input types, attributes, validations)
- Semantic tags and uses
- Web Accessibility
- Meta tags
- Media tags: image, audio, video
- SEO using HTML tags
- IFrames

---

## Important CSS Topics

- Box Model
- Cascading and Specificity
- Flexbox
- Grid
- Selectors
- Pseudo-class vs Pseudo-elements
- Measurement Units (absolute vs relative, and best practices)
- Positions
- Animations and Transitions
- z-index
- Accessibility
- px vs rem vs vh vs vw

---

## Important JavaScript Topics

- Working of JS
  - Execution Context
  - Callstack
- Data Types
  - Primitive Types (Immutable)
    - String, Boolean, Number, Symbol, Null, Undefined, BigInt
  - Non-Primitive Types (Mutable)
    - Array (map, filter, reduce, splice, slice, forEach)
    - Object (freeze, seal, isFrozen, isSealed)
- Pass by value vs pass by reference
- let / var / const
- Hoisting & Temporal Dead Zone
- Illegal shadowing
- Scope & Scope chaining
- Pure Functions
- Mutable/Immutable data types
- Shallow vs Deep copy
- DOM (DOM methods) and BOM
- Critical Rendering Path
- Functions
  - Declaration, Expression, Arrow Functions, IIFE
  - Functional Programming
- this keyword
- Call, Apply, Bind
- Closures and their uses
- Callbacks and Callback Hell
- Promises and chaining
  - Promise.all(), allSettled(), any(), race()
- Async/Await
- Currying
- Debouncing & Throttling
- Event Propagation (Bubbling, Capturing, Delegation)
- Prototype and Prototypal Inheritance
- Memoization
- Map and Set
- Generator Functions
- JS Engine internals
- Event Loop and Microtasks
- Important Events (DOMContentLoaded, load, beforeunload, unload)
- async/defer scripts
- Polyfills (Promise, map, reduce, filter, fetch API, etc.)
- Web APIs
- setTimeout, setInterval
- Higher Order Functions
- Module Pattern
- [Important Design Patterns (JS & React)](https://javascriptpatterns.vercel.app/patterns)

---

## Practice Time!

Practice is key! Start with conceptual questions and build basic JS apps.

Recommended resources:

- [LeetCode 30 Days of JavaScript](https://leetcode.com/studyplan/30-days-of-javascript/)
- [BigFrontend JavaScript Problems](https://bigfrontend.dev/)

Build these small apps to solidify your skills:

- Star Rating
- Flipkart Search bar with debouncing/throttle
- Typeahead/autocomplete search bar
- Todo List with CRUD
- Carousel, Accordion, Popover components
- Infinite Scroll
- Tic-Tac-Toe
- Image gallery (infinite scroll, pagination, search)
- Poll widget
- Event Emitter
- Kanban board with tasks/subtasks
- Basic Chat Application
- Comment Widget (nested replies, delete like Facebook)
- Food Ordering App (Search, Sort, Filter, Cart)
- Calculator (basic & advanced operations)
- Progress Bar (start, pause, restart)
- Analog Clock
- Day Calendar
- Todo List with Drag and Drop

---

## Web Fundamentals

- Web Performance & Optimization
  - Lazy Loading
  - Code splitting
  - Caching services
  - Asset optimization
  - Fast rendering & proper bundling
- Web Sockets
- Long polling & Short polling
- Webhooks
- SEO Basics
- Web Vitals
  - Largest Contentful Paint (LCP)
  - First Input Delay (FID)
  - Cumulative Layout Shift (CLS)
- Storing Data in Browser
  - LocalStorage, SessionStorage, Cookies
- Network requests
- DOM manipulation & security
- Security vulnerabilities
  - SSL Pinning
  - Cross-site scripting (XSS)
  - Cross-site Request Forgery (CSRF)
  - SQL Injection
- Design Patterns
- Cache strategies
  - Simple Cache
  - Mapped Cache

---

## TypeScript

- Static Typing
- Type Annotations
- Interfaces
- Classes & Inheritance
- Access Modifiers
- Generics
- Union & Intersection Types
- Enums
- Tuple Types
- Type Guards
- Decorators
- Optional Chaining & Nullish Coalescing
- Mapped Types
- Utility Types

---

## Frontend System Design

Resources to master system design for frontend:

- [Front-End Engineer YouTube Channel](https://www.youtube.com/watch?v=5vyKhm2NTfw&list=PLI9W87-Dqn7j_x6QtR6sUjycJR7nQLBqT)
- [Chirag Goel YouTube Channel](https://www.youtube.com/watch?v=sV_4pOGosnU&list=PL4CFloQ4GGWICE0Tz6iXKfN3XWkXRlboU)
- [BigFrontend Design Questions](https://bigfrontend.dev/design)
- [GreatFrontend Design Questions](https://www.greatfrontend.com/system-design)

### System Design Answer Framework

There is no single “best” solution; interviewers expect structured answers and creativity.

---

## Important React Topics

- Hooks: useState, useEffect, useCallback, useMemo, useRef, useReducer, useContext, useId, useLayoutEffect (prefer useEffect), useFormStatus, useFormState, useOptimistic, Custom Hooks
- React internals:
  - Reconciliation & Diffing Algorithm
  - JSX compilation
  - React keys (avoid using index as key if list changes)
  - Virtual DOM
  - React Fiber
- React Lifecycle (Class & Functional)
- Hooks vs Class Components
- Automatic Batching
- Async State Updates
- State Management (Context API, Redux)
- React with TypeScript
- Props & Prop Drilling
- Class vs Functional Components
- Webpack basics
- Sharing data between siblings via parent callbacks
- Default and Named Exports/Imports
- Performance Optimization:
  - Image optimization and caching
  - Memoization with useCallback and useMemo
  - Lazy loading images and code splitting
  - Localizing state
- React Design Patterns:
  - Container/Presentational
  - Higher-Order Components
  - Render Props
  - Hooks Pattern
  - Provider Pattern
  - Compound Pattern
- Redux principles:
  - Single source of truth
  - State is read-only
  - Changes via pure reducers
- Architecture:
  - Monolithic
  - Micro Frontend
  - Monorepo
- Unit Testing
- Routing (dynamic, secure, public)
- Next.js basics (SSR, CSR)

### New React 19 Topics

- React Compiler
- Action
- Server Components
- `'use server'` and `'use client'`
- Better SEO
- New Hooks: useFormStatus, useFormState, useOptimistic

---

## Next.js

- What is Next.js
- Why use Next.js & features
- getStaticProps
- getServerSideProps
- Difference between getStaticProps & getServerSideProps

---

## Important React Native Topics

- Hooks
- React Native threads (Main thread, JS thread)
- Bridge
- Interaction Manager
- Set Native Props
- React Native Builder Bob (for libraries)
- Yoga layout engine
- Performance issues & optimizations
- Build process
- React Native internals
- Optimizing React Native Apps:
  - Use FlatList/SectionList for large lists
  - Minimize UI-JS thread interaction
  - Cache services & images
  - Use optimized images/SVGs
  - Memoize expensive calculations with useCallback/useMemo
  - Minimize re-renders
  - Optimize state management

---

## Testing

- Unit Testing
- End-to-End Testing
- Component Testing
- Integration Testing
