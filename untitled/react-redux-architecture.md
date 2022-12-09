# react-redux-architecture

## React Component Lifecycle

* **React Docs: Component Specs and Lifecycle**\
  [https://facebook.github.io/react/docs/component-specs.html](https://facebook.github.io/react/docs/component-specs.html)\
  The official React docs page on component lifecycle
* **Understanding the React Component Lifecycle**\
  [http://busypeoples.github.io/post/react-component-lifecycle/](http://busypeoples.github.io/post/react-component-lifecycle/)\
  A good look at which lifecycle methods run in which situations, as well as the signatures of each method.
* **Dissecting React Lifecycle Methods**\
  [https://medium.com/@fay\_jai/dissecting-reactjs-lifecycle-methods-be4fdea11c6d](https://medium.com/@fay\_jai/dissecting-reactjs-lifecycle-methods-be4fdea11c6d)\
  Breaks the lifecycle methods down into "mount/unmount" and "update" categories, and describes the purpose and use of each.
* **The React Component Lifecycle**\
  [https://www.kirupa.com/react/component\_lifecycle.htm](https://www.kirupa.com/react/component\_lifecycle.htm)\
  Another useful description of the order and purpose of the lifecycle methods.
* **React In-Depth: The React Life Cycle**\
  [https://developmentarc.gitbooks.io/react-indepth/content/](https://developmentarc.gitbooks.io/react-indepth/content/)\
  A deep dive into the lifecycle methods, and various techniques for using them.

## React Component Management

* **Presentational and Container Components**\
  [https://medium.com/@dan\_abramov/smart-and-dumb-components-7ca2f9a7c7d0](https://medium.com/@dan\_abramov/smart-and-dumb-components-7ca2f9a7c7d0)\
  Dan Abramov's foundational article on classifying components based on intent and behavior. A must-read for anyone using React.
* **Mixins Are Dead. Long Live Composition**\
  [https://medium.com/@dan\_abramov/mixins-are-dead-long-live-higher-order-components-94a0d2f9e750](https://medium.com/@dan\_abramov/mixins-are-dead-long-live-higher-order-components-94a0d2f9e750)\
  A look at some of the issues with using mixins, and reasons why higher-order components are (usually) an improvement.
* **How to use Classes and Sleep at Night**\
  [https://medium.com/@dan\_abramov/how-to-use-classes-and-sleep-at-night-9af8de78ccb4](https://medium.com/@dan\_abramov/how-to-use-classes-and-sleep-at-night-9af8de78ccb4)\
  Some pragmatic opinions on when and how to use the ES6 "class" keyword, particularly in relation to React components.
* **Higher Order Components: Theory and Practice**\
  [http://engineering.blogfoster.com/higher-order-components-theory-and-practice/](http://engineering.blogfoster.com/higher-order-components-theory-and-practice/)\
  Gives practical use cases for HOCs, such as authentication, routing, and data management, with samples.
* **Sharing and Testing Code in React with Higher Order Components**\
  [http://blog.carbonfive.com/2016/02/02/sharing-and-testing-code-in-react-with-higher-order-components/](http://blog.carbonfive.com/2016/02/02/sharing-and-testing-code-in-react-with-higher-order-components/)\
  Demonstrates extracting HOCs from existing code, and testing them.
* **React Higher Order Components in depth**\
  [https://medium.com/@franleplant/react-higher-order-components-in-depth-cf9032ee6c3e](https://medium.com/@franleplant/react-higher-order-components-in-depth-cf9032ee6c3e)\
  A very detailed article looking at some advanced HoC patterns
* **8 no-Flux strategies for React component communication**\
  [http://andrewhfarmer.com/component-communication/](http://andrewhfarmer.com/component-communication/)\
  Very helpful list of ways to have React components communicate back and forth
* **How to communicate between React components**\
  [http://ctheu.com/2015/02/12/how-to-communicate-between-react-components/](http://ctheu.com/2015/02/12/how-to-communicate-between-react-components/)\
  Another good list of component communication strategies
* **How to Write a Google Maps React Component**\
  [https://www.fullstackreact.com/articles/how-to-write-a-google-maps-react-component/](https://www.fullstackreact.com/articles/how-to-write-a-google-maps-react-component/)\
  Demonstrates how to wrap a third-party component that has an imperative API, lazy-loading the dependencies, and more.
* **Building SVG Maps with React**\
  [https://blog.komand.com/building-svg-maps-with-react](https://blog.komand.com/building-svg-maps-with-react)\
  Demonstrates building a component that zooms and pans SVG graphics based on user input.
* **How to Sprinkle ReactJS into an Existing Web Application**\
  [https://scotch.io/tutorials/how-to-sprinkle-reactjs-into-an-existing-web-application](https://scotch.io/tutorials/how-to-sprinkle-reactjs-into-an-existing-web-application)\
  Looks at how to incrementally add some React-based functionality into an existing app.
* **Leveling Up with React: Container Components**\
  [https://css-tricks.com/learning-react-container-components/](https://css-tricks.com/learning-react-container-components/)\
  Describes the container component pattern and how to use it to split up responsibilities between fetching and displaying data.
* **Finding `state`'s place with React and Redux**\
  [https://medium.com/@adamrackis/finding-state-s-place-with-react-and-redux-e9a586630172](https://medium.com/@adamrackis/finding-state-s-place-with-react-and-redux-e9a586630172) A look at when and how using React component state may be useful, even when using Redux for primary app state
* **Dataflow through React**\
  [https://jurassix.gitbooks.io/dataflow-through-react/content/index.html](https://jurassix.gitbooks.io/dataflow-through-react/content/index.html)\
  An online book that covers a number of topics on React components and data flow.
* **A case for setState**\
  [https://medium.com/@zackargyle/a-case-for-setstate-1f1c47cd3f73](https://medium.com/@zackargyle/a-case-for-setstate-1f1c47cd3f73)\
  An article arguing that React component state still has a number of uses.
* **Smart and Dumb Components in React**\
  [http://jaketrent.com/post/smart-dumb-components-react/](http://jaketrent.com/post/smart-dumb-components-react/)\
  Another look at ways to conceptually categorize components based on responsibilities, and some ways you can organize your code based on those concepts.
* **Functional Components vs. Stateless Functional Components vs. Stateless Components**\
  [https://tylermcginnis.com/functional-components-vs-stateless-functional-components-vs-stateless-components-630fdfd90c9c](https://tylermcginnis.com/functional-components-vs-stateless-functional-components-vs-stateless-components-630fdfd90c9c)\
  Clarifies the meaning of the terms, which are often used in overlapping ways.
* **React Component Jargon as of August 2016**\
  [https://medium.com/@arcomito/react-component-jargon-as-of-august-2016-28451d8ceb1d](https://medium.com/@arcomito/react-component-jargon-as-of-august-2016-28451d8ceb1d)\
  A very useful glossary of widely-used terms describing React components
* **Dynamically Rendering React Components**\
  [https://wail.es/dynamically-rendering-react-components/](https://wail.es/dynamically-rendering-react-components/)\
  Examples of how to dynamically determine which React component to render
* **Higher Order Components: A React Application Design Pattern**\
  [https://www.sitepoint.com/react-higher-order-components/](https://www.sitepoint.com/react-higher-order-components/)\
  A discussion of how to use Higher Order Components to keep your React applications tidy, well structured and easy to maintain. Also, how pure functions keep code clean and how these same principles can be applied to React components.
* **The React Controller View Pattern**\
  [http://blog.andrewray.me/the-reactjs-controller-view-pattern/](http://blog.andrewray.me/the-reactjs-controller-view-pattern/)\
  Describes using top-level components to hold state and pass it to children as props
* **Functional React Serie - Part 1: Get your App outta my Component**\
  [https://medium.com/@adamterlson/functional-react-series-part-1-get-your-app-outta-my-component-92656ae13e25](https://medium.com/@adamterlson/functional-react-series-part-1-get-your-app-outta-my-component-92656ae13e25)\
  Part 1 in a series about writing React applications by treating components as functions, not templates.
* **How to handle state in React: The Missing FAQ**\
  [https://medium.com/react-ecosystem/how-to-handle-state-in-react-6f2d3cd73a0c](https://medium.com/react-ecosystem/how-to-handle-state-in-react-6f2d3cd73a0c)\
  An article that dispels misunderstandings and answers common questions about how to handle state in React.
* **Where to Hold React Component Data: state, store, static, and this**\
  [https://medium.freecodecamp.com/where-do-i-belong-a-guide-to-saving-react-component-data-in-state-store-static-and-this-c49b335e2a00](https://medium.freecodecamp.com/where-do-i-belong-a-guide-to-saving-react-component-data-in-state-store-static-and-this-c49b335e2a00)\
  A great summary of different places to store state, and when and why you should use each.
* **Function as Child Components**\
  [https://medium.com/merrickchristensen/function-as-child-components-5f3920a9ace9](https://medium.com/merrickchristensen/function-as-child-components-5f3920a9ace9)\
  Explains the "function as a child" technique as an alternative to Higher Order Components

## React and AJAX

* **React AJAX Best Practices**\
  [http://andrewhfarmer.com/react-ajax-best-practices/](http://andrewhfarmer.com/react-ajax-best-practices/)\
  Covers four ways to approach managing queries and data fetching.
* **AJAX/HTTP Library Comparison**\
  [http://andrewhfarmer.com/ajax-libraries/](http://andrewhfarmer.com/ajax-libraries/)\
  A useful overview of the most popular AJAX libraries, including platform support and feature comparisons.
* **Implementing React Redux with GraphQL**\
  [https://marufsarker.github.io/blog/posts/2016/05/09/react-redux-with-graphql.html](https://marufsarker.github.io/blog/posts/2016/05/09/react-redux-with-graphql.html)\
  Walks through the implementation of a server/client Todo app that uses GraphQL mutations for the async actions.
* **Rendering Backend Requests with React**\
  [https://blog.boldlisting.com/rendering-backend-requests-with-react-7e493103c2b6](https://blog.boldlisting.com/rendering-backend-requests-with-react-7e493103c2b6)\
  Describes a pattern for dealing with components that depend on loading data from a backend
* **Build a React + Flux App with User Authentication**\
  [https://scotch.io/tutorials/build-a-react-flux-app-with-user-authentication](https://scotch.io/tutorials/build-a-react-flux-app-with-user-authentication)\
  Builds a React app that calls a remote API and authenticates users. Uses a specific auth provider and basic Flux implementation, but the concepts are widely applicable.
* **Building Realtime Collaborative Offline-First Apps with React, Redux, PouchDB, and Websockets**\
  [http://blog.yld.io/2015/11/30/building-realtime-collaborative-offline-first-apps-with-react-redux-pouchdb-and-web-sockets/](http://blog.yld.io/2015/11/30/building-realtime-collaborative-offline-first-apps-with-react-redux-pouchdb-and-web-sockets/)\
  A blog post and sample project demonstrating various layers of client-server syncing, eventually driving a Redux store and React UI.

## React and Forms

(Note: the "linked state mixin" and "two-way binding" approaches described in some of these articles are still valid, but _mostly_ discouraged at this point. The more idiomatic approach is "one-way data flow" with "controlled inputs".)

* **React Docs: Forms**\
  [https://facebook.github.io/react/docs/forms.html](https://facebook.github.io/react/docs/forms.html)\
  The React documentation page on forms. Describes "controlled" and "uncontrolled" form inputs.
* **Learn Raw React: Ridiculously Simple Forms**\
  [http://jamesknelson.com/learn-raw-react-ridiculously-simple-forms/](http://jamesknelson.com/learn-raw-react-ridiculously-simple-forms/)\
  Covers the basics of implementing form rendering, updates, and validation, in plain JS
* **Forms in React and Redux**\
  [http://x-team.com/2016/02/tutorial-forms-in-react-and-redux/](http://x-team.com/2016/02/tutorial-forms-in-react-and-redux/)\
  Demonstrates building a simple set of wrapper components to manage forms using React and Redux
* **Form Validation Tutorial with React.js**\
  [https://html5hive.org/reactjs-form-validation-tutorial/](https://html5hive.org/reactjs-form-validation-tutorial/)\
  A good example of setting up form validation in React
* **Not-so-simple Forms with React**\
  [http://www.randseay.com/articles/forms-with-react/](http://www.randseay.com/articles/forms-with-react/)\
  Explains how to set up more advanced form scenarios such as optional or repeatable sections.
* **Managing state and controlled form fields with React**\
  [https://blog.iansinnott.com/managing-state-and-controlled-form-fields-with-react/](https://blog.iansinnott.com/managing-state-and-controlled-form-fields-with-react/)\
  Describes the concepts of "controlled" and "uncontrolled" inputs.
* **Two-Way Data Binding and Form Validation in React**\
  [https://medium.com/@thejenniekim/two-way-data-binding-and-form-validation-in-react-9d0b15123176](https://medium.com/@thejenniekim/two-way-data-binding-and-form-validation-in-react-9d0b15123176)\
  Another demonstration of building a form with some logic and validation.
* **Using React's state to manage data entry**\
  [https://medium.com/@adamrackis/using-reacts-state-to-manage-data-entry-ed92e4fd1a42](https://medium.com/@adamrackis/using-reacts-state-to-manage-data-entry-ed92e4fd1a42) Describes how to manage data for forms using React component state and some wrapper components.
* **Handling React Forms with Mobx Observables**\
  [https://blog.risingstack.com/handling-react-forms-with-mobx-observables/](https://blog.risingstack.com/handling-react-forms-with-mobx-observables/)\
  Some examples of working with forms in React, using MobX for the data management.
* **Forms in React and Redux**\
  [http://x-team.com/2016/02/tutorial-forms-in-react-and-redux/](http://x-team.com/2016/02/tutorial-forms-in-react-and-redux/)\
  A good example of how to set up form handling in conjunction with a Redux store.
* **React Form Components**\
  [http://donavon.js.org/react-forms/](http://donavon.js.org/react-forms/)\
  A look at controlled vs uncontrolled inputs, with a useful note about issues with controlled inputs and certain browsers.
* **React "controlled" vs "uncontrolled" inputs**\
  [https://gist.github.com/markerikson/d71cfc81687f11609d2559e8daee10cc](https://gist.github.com/markerikson/d71cfc81687f11609d2559e8daee10cc)\
  An explanation of the terms "controlled inputs" and "uncontrolled inputs"
* **Uncontrolled components are an anti-pattern**\
  [https://medium.com/@jedwards8/uncontrolled-components-are-an-anti-pattern-abbdd86fd39e](https://medium.com/@jedwards8/uncontrolled-components-are-an-anti-pattern-abbdd86fd39e)\
  Argues that uncontrolled components are a bad idea and should be avoided.
* **ReactJS and controlled forms**\
  [http://leftdevel.com/blog/reactjs-controlled-forms/](http://leftdevel.com/blog/reactjs-controlled-forms/)\
  A look at the difference between controlled and uncontrolled inputs, and some problems that can come from using uncontrolled inputs.
* **Managing React Controlled Component State**\
  [http://spraso.com/managing-react-controlled-component-state/](http://spraso.com/managing-react-controlled-component-state/)\
  Some short examples of how to properly manage state for controlled inputs

## Project File Structure

* **Scaling React.js Applications**\
  [https://vimeo.com/168648012](https://vimeo.com/168648012)\
  Talk about managing large react.js applications. Covers "Feature" structure, redux-saga and CSS modules.
* **Organizing Large React Applications**\
  [http://engineering.kapost.com/2016/01/organizing-large-react-applications/](http://engineering.kapost.com/2016/01/organizing-large-react-applications/)\
  Describes "File-Type First", "Feature First / Pods" approaches, as well as other related structure issues.
* **Four Strategies for Organizing Code**\
  [https://medium.com/@msandin/strategies-for-organizing-code-2c9d690b6f33](https://medium.com/@msandin/strategies-for-organizing-code-2c9d690b6f33)\
  Describes "by component", "by toolbox", "by layer", and "by kind" approaches.
* **Rules for Structuring (Redux) Applications**\
  [http://jaysoo.ca/2016/02/28/organizing-redux-application/](http://jaysoo.ca/2016/02/28/organizing-redux-application/)\
  Gives several useful rules for structuring code, with examples.
* **A Better File Structure for React/Redux Applications**\
  [http://marmelab.com/blog/2015/12/17/react-directory-structure.html](http://marmelab.com/blog/2015/12/17/react-directory-structure.html)\
  Suggests a domain-based structure, with tests kept alongside the code they relate to.
* **Route-Based Folder Structure**\
  [https://gist.github.com/ryanflorence/daafb1e3cb8ad740b346](https://gist.github.com/ryanflorence/daafb1e3cb8ad740b346)\
  Ryan Florence, an author of React Router, gives his suggested file structure.
* **How to Better Organize Your React Applications?**\
  [https://medium.com/@alexmngn/how-to-better-organize-your-react-applications-2fd3ea1920f1](https://medium.com/@alexmngn/how-to-better-organize-your-react-applications-2fd3ea1920f1)\
  Another feature-style approach, describing things in terms of "components", "scenes", and "services".
* **Fractal Project Structure**\
  [https://github.com/davezuko/react-redux-starter-kit/wiki/Fractal-Project-Structure](https://github.com/davezuko/react-redux-starter-kit/wiki/Fractal-Project-Structure)\
  Docs from the React Redux Starter Kit project describing their "Fractal Project Structure" concept, and advice for file and app organization.

## Redux Architecture

* **Reddit: "Redux - Reducer composition without slicing state?"**\
  [https://www.reddit.com/r/javascript/comments/42ey9e/redux\_reducer\_composition\_without\_slicing\_state/](https://www.reddit.com/r/javascript/comments/42ey9e/redux\_reducer\_composition\_without\_slicing\_state/)\
  Some very informative discussion on how to organize reducers and actions.
* **Wordpress Calypso: Our Approach to Data**\
  [https://github.com/Automattic/wp-calypso/blob/master/docs/our-approach-to-data.md](https://github.com/Automattic/wp-calypso/blob/master/docs/our-approach-to-data.md)\
  The team behind Wordpress's new admin panel looks at their migration from emitters to Flux to Redux, and describes how they organize their state tree, use selectors to extract state, run queries with components, and persist their store state through refreshes.
* **So you've screwed up your Redux store - or, why Redux makes refactoring easy**\
  [https://blog.boldlisting.com/so-youve-screwed-up-your-redux-store-or-why-redux-makes-refactoring-easy-400e19606c71](https://blog.boldlisting.com/so-youve-screwed-up-your-redux-store-or-why-redux-makes-refactoring-easy-400e19606c71)\
  Describes some useful practices for organizing Redux actions, reducers, and selectors.
* **How we reduced boilerplate and handled asynchronous actions with Redux**\
  [https://blog.algolia.com/how-we-reduced-boilerplate-and-handled-asynchronous-actions-with-redux/](https://blog.algolia.com/how-we-reduced-boilerplate-and-handled-asynchronous-actions-with-redux/)\
  A look at conventions that have helped the Algolia team write Redux apps.
