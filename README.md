# Friday Deep Dive

Epicodus-React, Week 3 Independent Project

_Nathan Stewart_ 09.22.2017

## Discription

This project is a plan for my unstructured study/project day. I will lay out my goals for the day, get started, then provide a list of what was actually accomplished at the end of the day. I will also provide links to any relevant material that was completed.

## Morning Plan/Goal

  * Thorough review of Epicodus curriculum from the last two weeks. Focus on personal sticky points: Webpack configuration, component lifecycle methods, lifting state, and unit testing.

  * Watch and study React and React-Reduct video series on [Egghead.io](https://egghead.io/technologies/react).
    * Start Learning React - Joe Maddalone
    * Getting Started with Redux - Dan Abramov
    * Building React Applications with Idiomatic Redux - Dan Abramov


  * Refactor project from last Friday to bring into line with the current week curriculum, and possibly some new tricks from the Egghead.io courses.

## Actual Study/Accomplishments

  * Review of webpack configuration:
    * [Building an Environment](https://www.learnhowtoprogram.com/react/react-fundamentals/building-an-environment)
    * [Building an Environment: Development Server & Hot Module Replacement](https://www.learnhowtoprogram.com/react/react-fundamentals/building-an-environment-development-server-hot-module-replacement)
    * [Webpack-The Confusing Parts](https://medium.com/@rajaraodv/webpack-the-confusing-parts-58712f8fcad9)
    * [React Tutorial 1.5: Utilizing Webpack and Babel to build a React.js App](https://tylermcginnis.com/react-js-tutorial-1-5-utilizing-webpack-and-babel-to-build-a-react-js-app/)
    * I still find this rather confusing and complicated, I think nothing but practice through building more apps will help at this point.


  * Review loops in jsx, conditional rendering, and refs. I looked deeper into refs.
     * [Conditional Rendering, Loops, and Refs](https://www.learnhowtoprogram.com/react/react-fundamentals/conditional-rendering-loops-and-refs)
     * [Refs and the DOM](https://facebook.github.io/react/docs/refs-and-the-dom.html)
     * [Refs in React : All you need to know !](https://hackernoon.com/refs-in-react-all-you-need-to-know-fb9c9e2aeb81)


  * Review lifting state.
    * [Component Trees and Lifting State](https://www.learnhowtoprogram.com/react/react-fundamentals/component-trees-and-lifting-state)
    * [Lifting State Up](https://facebook.github.io/react/docs/lifting-state-up.html)
    * [Best Practices and Lifting Complex State](https://www.learnhowtoprogram.com/react/react-fundamentals/best-practices-and-lifting-complex-state)


  * Review component lifecycle methods.
    * [Component Lifecycle Methods](https://www.learnhowtoprogram.com/react/react-fundamentals/component-lifecycle-methods)
    * [React.Component](https://facebook.github.io/react/docs/react-component.html)
    * [React component’s lifecycle.](https://medium.com/react-ecosystem/react-components-lifecycle-ce09239010df)
    * [Lifecycle Methods in Action](https://www.learnhowtoprogram.com/react/react-fundamentals/lifecycle-methods-in-action)


  * Video series: [Start Learning React - Joe Maddalone](https://egghead.io/courses/start-learning-react)
    * Number 8  offers an interesting tip on custom proptype validation beyond what we have learned in the Epicodus curriculum.
    * Number 10 gives a succinct and understandable explanation of refs.
    * Number 12 gives great examples of component lifecycle methods, along with how and when to use them.
    * Number 17 offers a nice jsx syntax explanation.
    * Number 20 gives a nice example of how to make components more reusable.


  * Review Redux
    * [Introduction to Redux: Application](https://www.learnhowtoprogram.com/react/react-and-redux/introduction-to-redux-application)
    * [Unit Testing Reducers](https://www.learnhowtoprogram.com/react/react-and-redux/unit-testing-reducers)
      * I still need a lot of work here. I attempted to reproduce the CLOSE_TICKET example given at the end of class yesterday and was unsuccessful.
    * [Flux Architecture](https://www.learnhowtoprogram.com/react/react-and-redux/flux-architecture)
    * [Client-Side Routing](https://www.learnhowtoprogram.com/react/react-and-redux/client-side-routing)
    * [Managing State in Multiple Routes](https://www.learnhowtoprogram.com/react/react-and-redux/managing-state-in-multiple-routes)
    * [Advanced Routing with React-Router & Removing Items from State](https://www.learnhowtoprogram.com/react/react-and-redux/advanced-routing-with-react-router-removing-items-from-state)
    * Video series: [Getting Started with Redux - Dan Abramov](https://egghead.io/courses/getting-started-with-redux)
      * Number 3 gives an excellent visual example of pure and impure functions.
      * Number 5 gives a good simple reducer and tests example, but it is not helpful for more complicated actions like the CLOSE_TICKET test.
      * Numbers 9 and 10 give a good look at the object spread operator as a way to avoid state mutation in reducers, as well as the deepfreeze library, which enforces the no mutation rule.
      * Number 13 introduces the reducer composition pattern, which I found rather confusing. I bookmarked a search of articles on this for weekend study.
      * Number 14 clarifies and makes the composition patter much easier with the combineReducers function.
      * Numbers 20-23 give good examples and explanations of separating presentational and container components.
      * Numbers 24 - 26 gave me a much better understanding of why we provide our store in a Provider container component, and what is going on behind the scenes.


  * Information overload, done for today!
    * Although I did not write any code, today was extremely helpful to me. I appreciate being given the time to dig deep on some of these concepts during "class time", as opposed to having to give up what little free time I have lately. That being said, I will probably spend some time this weekend refactoring my [Medication Tracker](https://github.com/GStewartN/meds-tracker) from las week to employ lessons from this week.
