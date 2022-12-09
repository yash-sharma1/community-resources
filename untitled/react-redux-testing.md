# react-redux-testing

* **Approaches to Testing React Components**\
  [http://reactkungfu.com/2015/07/approaches-to-testing-react-components-an-overview/](http://reactkungfu.com/2015/07/approaches-to-testing-react-components-an-overview/)\
  A great starting point to testing, looking at the main ways you can test component structure and state handling
* **Simple React/Redux Testing**\
  [https://medium.com/@caljrimmer/simple-react-redux-testing-cd579d4c2103](https://medium.com/@caljrimmer/simple-react-redux-testing-cd579d4c2103)\
  Looks at how to test rendering, behavior, and state of an application
* **Test Driven React Tutorial**\
  [http://spencerdixon.com/blog/test-driven-react-tutorial.html](http://spencerdixon.com/blog/test-driven-react-tutorial.html)\
  Describes project setup and basic approaches, using the common stack of Webpack+Karma+Mocha+Chai+Sinon
* **How to Test React.js Components**\
  [https://nemisj.com/how-to-test-react-js-components/](https://nemisj.com/how-to-test-react-js-components/)\
  Covers what to test, and how to test things like props and shallow rendering
* **Unit Testing a Redux App**\
  [https://www.codementor.io/reactjs/tutorial/redux-unit-test-mocha-mocking](https://www.codementor.io/reactjs/tutorial/redux-unit-test-mocha-mocking)\
  Example ways to test pieces of a Redux app, including actions, reducers, and middleware
* **React-Boilerplate Testing Docs**\
  [https://github.com/mxstbr/react-boilerplate/blob/v3.0.0/docs/testing/unit-testing.md](https://github.com/mxstbr/react-boilerplate/blob/v3.0.0/docs/testing/unit-testing.md)\
  [https://github.com/mxstbr/react-boilerplate/blob/v3.0.0/docs/testing/component-testing.md](https://github.com/mxstbr/react-boilerplate/blob/v3.0.0/docs/testing/component-testing.md)\
  Useful description of how to use Mocha, Expect, and Enzyme to test React and Redux code
* **Testing React Applications**\
  [http://12devsofxmas.co.uk/2015/12/day-2-testing-react-applications/](http://12devsofxmas.co.uk/2015/12/day-2-testing-react-applications/)\
  A long, in-depth article describing approaches and use of Tape, React TestUtils, and Enzyme
* **TDD and React Components**\
  [https://medium.com/@nackjicholsonn/tdd-and-react-components-5ae5a9a5a7bf](https://medium.com/@nackjicholsonn/tdd-and-react-components-5ae5a9a5a7bf)\
  Detailed example of using TDD to design and develop a React component, using Teaspoon for testing
* **Testing Redux Applications**\
  [http://randycoulman.com/blog/2016/03/15/testing-redux-applications/](http://randycoulman.com/blog/2016/03/15/testing-redux-applications/)\
  [http://randycoulman.com/blog/categories/getting-testy/](http://randycoulman.com/blog/categories/getting-testy/)\
  A great writeup on how to specifically deal with testing pieces of a Redux app. The "Getting Testy" post series also has a lot of really good idea on how to go about writing tests and what kinds of things should be tested.
* **Testing with Mocha and Webpack**\
  [http://randycoulman.com/blog/2016/03/22/testing-with-mocha-and-webpack/](http://randycoulman.com/blog/2016/03/22/testing-with-mocha-and-webpack/)\
  [http://randycoulman.com/blog/2016/04/05/more-on-testing-with-mocha-and-webpack/](http://randycoulman.com/blog/2016/04/05/more-on-testing-with-mocha-and-webpack/)\
  Some excellent information on setting up a good test environment, including use of the mocha-webpack tool.
* **Testing React Components with Teaspoon and Unexpected**\
  [http://dchambers.github.io/articles/testing-react-components-with-teaspoon-and-unexpected/](http://dchambers.github.io/articles/testing-react-components-with-teaspoon-and-unexpected/)\
  A short but useful look at a couple testing libraries and ways to use them.
* **Unit Testing React Components and Redux Reducers**\
  [http://pebblecode.com/blog/react-redux-unit-testing/](http://pebblecode.com/blog/react-redux-unit-testing/)\
  Some basic examples for testing reducers and components.
* **Getting Started with TDD in React**\
  [https://semaphoreci.com/community/tutorials/getting-started-with-tdd-in-react](https://semaphoreci.com/community/tutorials/getting-started-with-tdd-in-react)\
  Covers a typical Mocha+Chai+JSDOM+Enzyme setup, talks about why/how/what to test, and walks through several examples.
* **Testing React Applications**\
  [https://youtu.be/KBhHsYlF4mQ](https://youtu.be/KBhHsYlF4mQ)\
  A fantastic talk that goes through many important details of trying to test React components under JSDOM.
* **Testing in React: Getting Off the Ground**\
  [https://medium.com/javascript-inside/testing-in-react-getting-off-the-ground-5f569f3088a](https://medium.com/javascript-inside/testing-in-react-getting-off-the-ground-5f569f3088a)\
  A look at approaches and ways to start testing React components
* **Testing React and Redux**\
  [http://silvenon.com/testing-react-and-redux/](http://silvenon.com/testing-react-and-redux/)\
  A three-part article that shows how to set up Ava and Babel, then walks through testing Redux code (action creators, reducers, selectors, thunks, and sagas), and React components.
* **Testing React Applications Examples**\
  [https://github.com/mxstbr/react-testing](https://github.com/mxstbr/react-testing)\
  A repo showcasing how to test various parts of a common React/Redux app using Mocha, expect and enzyme
* **Unit Testing Redux Container Components**\
  [http://pebblecode.com/blog/testing-redux-containers/](http://pebblecode.com/blog/testing-redux-containers/)\
  Demonstrates techniques for properly testing Redux-connected React components using a mock store.

## General Testing, Tools, and Setup

* **Javascript Testing: Unit vs Functional vs Integration**\
  [https://www.sitepoint.com/javascript-testing-unit-functional-integration/](https://www.sitepoint.com/javascript-testing-unit-functional-integration/)\
  A comparison of the various levels of tests you can run, and what roles they play in development.
* **Reddit - "Karma/Mocha/Chai/Sinon setup"**\
  [https://www.reddit.com/r/javascript/comments/4217x6/ive\_spent\_six\_hours\_attempting\_to\_set\_up/](https://www.reddit.com/r/javascript/comments/4217x6/ive\_spent\_six\_hours\_attempting\_to\_set\_up/)\
  Reddit user Cody\_Chaos describes his approach to running unit tests under Node with Mocha, and integration tests in a browser with Karma. Includes several useful config setup snippets.
* **Setting Up Javascript Testing Tools for ES6**\
  [http://x-team.com/2016/05/setting-up-javascript-testing-tools-for-es6/](http://x-team.com/2016/05/setting-up-javascript-testing-tools-for-es6/)\
  Tips on configuring tools to work with ES6 code, and writing tests using ES6
* **Keep Calm and Love Javascript Unit Tests - Part 2: Asynchronism**\
  [http://www.theodo.fr/blog/2016/06/keep-calm-and-love-javascript-unit-tests-part-2-asynchronism/](http://www.theodo.fr/blog/2016/06/keep-calm-and-love-javascript-unit-tests-part-2-asynchronism/)\
  Useful tips for testing asynchronous behavior under Mocha.
* **ESLint Part 1: Exploration**\
  [https://blog.scottnonnenberg.com/eslint-part-1-exploration/](https://blog.scottnonnenberg.com/eslint-part-1-exploration/)\
  A solid look at what ESLint is, how you can use it to help keep your code clean, and a number of useful linting plugins that are available.
* **Keep Calm and Love Javascript Unit Tests**\
  [http://www.theodo.fr/blog/2016/04/keep-calm-and-love-javascript-unit-tests-part-1/](http://www.theodo.fr/blog/2016/04/keep-calm-and-love-javascript-unit-tests-part-1/)\
  [http://www.theodo.fr/blog/2016/06/keep-calm-and-love-javascript-unit-tests-part-2-asynchronism/](http://www.theodo.fr/blog/2016/06/keep-calm-and-love-javascript-unit-tests-part-2-asynchronism/)\
  An introduction to using Mocha, Chai, and Sinon to write unit tests for various scenarios.
