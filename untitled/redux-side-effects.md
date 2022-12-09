# redux-side-effects

## Basic Concepts and Thunks

* **Stack Overflow: Dispatching Redux Actions with a Timeout**\
  [http://stackoverflow.com/questions/35411423/how-to-dispatch-a-redux-action-with-a-timeout/35415559#35415559](http://stackoverflow.com/questions/35411423/how-to-dispatch-a-redux-action-with-a-timeout/35415559#35415559)\
  Dan Abramov explains the basics of managing async behavior in Redux, walking through a progressive series of approaches (inline async calls, async action creators, thunk middleware).
* **Stack Overflow: Why do we need middleware for async flow in Redux?**\
  [http://stackoverflow.com/questions/34570758/why-do-we-need-middleware-for-async-flow-in-redux/34599594#34599594](http://stackoverflow.com/questions/34570758/why-do-we-need-middleware-for-async-flow-in-redux/34599594#34599594)\
  Dan Abramov gives reasons for using thunks and async middleware, and some useful patterns for using thunks.
* **Pure Functionality and Side Effects with Redux**\
  [https://blog.hivejs.org/building-the-ui-2/](https://blog.hivejs.org/building-the-ui-2/)\
  An overview of what side effects are, how they fit into Redux, and several approaches for managing them.

## Sagas

* **Master Complex Redux Workflows with Sagas**\
  [http://konkle.us/master-complex-redux-workflows-with-sagas/](http://konkle.us/master-complex-redux-workflows-with-sagas/)\
  Describes what sagas are, how Redux-Saga uses generators to run sagas, some potential concerns, and how to use them.
* **Stack Overflow: Why do we need middleware for async flux in Redux?**\
  [http://stackoverflow.com/questions/34570758/why-do-we-need-middleware-for-async-flow-in-redux/34623840#34623840](http://stackoverflow.com/questions/34570758/why-do-we-need-middleware-for-async-flow-in-redux/34623840#34623840)\
  A comparison of imperative thunks vs declarative sagas, and some of the benefits that sagas can provide for testing and decoupling of logic.
* **Managing Side Effects in React + Redux using Sagas**\
  [http://jaysoo.ca/2016/01/03/managing-processes-in-redux-using-sagas/](http://jaysoo.ca/2016/01/03/managing-processes-in-redux-using-sagas/)\
  Demonstrates various ways to implement a Timer app as a state machine, including using sagas to manage the periodic updates.
* **Persist Redux State By Using Sagas**\
  [http://engineering.invisionapp.com/post/persist-redux-state-by-using-sagas/](http://engineering.invisionapp.com/post/persist-redux-state-by-using-sagas/)\
  A very well-written set of examples showing how to use sagas to implement some complex store persistence logic.
* **Handling Async in Redux with Sagas**\
  [http://wecodetheweb.com/2016/01/23/handling-async-in-redux-with-sagas/](http://wecodetheweb.com/2016/01/23/handling-async-in-redux-with-sagas/)\
  Covers the basic concepts and syntax of sagas, and how they can improve testability.
* **Redux Saga conceptual diagram**\
  [https://twitter.com/kuy/status/731484272234663937](https://twitter.com/kuy/status/731484272234663937)\
  A useful diagram illustrating the various things a saga can do
* **"Redux Sagas benefits?"**\
  [https://www.reddit.com/r/reactjs/comments/4ng8rr/redux\_sagas\_benefits/](https://www.reddit.com/r/reactjs/comments/4ng8rr/redux\_sagas\_benefits/)\
  Discussion of when and why you might want to use sagas, with some great examples in the comments.
* **Manage Side Effects Efficiently with Redux Saga**\
  [https://youtu.be/QJVdcIlqGwc](https://youtu.be/QJVdcIlqGwc)\
  A presentation describing the concepts of generators and sagas.
* **Redux Saga conceptual diagram**\
  [https://qiita-image-store.s3.amazonaws.com/0/69860/8cc1a873-c675-9009-570d-9684da4a704f.png](https://qiita-image-store.s3.amazonaws.com/0/69860/8cc1a873-c675-9009-570d-9684da4a704f.png)\
  A nifty diagram from @kuy illustrating the general interaction of Redux Saga's async flow operators
* **"Redux Sagas Benefits?"**\
  [https://www.reddit.com/r/reactjs/comments/4ng8rr/redux\_sagas\_benefits/](https://www.reddit.com/r/reactjs/comments/4ng8rr/redux\_sagas\_benefits/)\
  Some great examples in the comments of how Redux Saga works and how to use it.
* **Async Operations using Redux-Saga**\
  [https://medium.com/@andresmijares25/async-operations-using-redux-saga-2ba02ae077b3](https://medium.com/@andresmijares25/async-operations-using-redux-saga-2ba02ae077b3)\
  An example of using Redux-Saga to coordinate multiple async calls based on another article's flight data scenario.

## Other

*   **The Problem with Redux... And How to Fix It** &#x20;

    [http://blog.javascripting.com/2016/05/21/the-problem-with-redux-and-how-to-fix-it/](http://blog.javascripting.com/2016/05/21/the-problem-with-redux-and-how-to-fix-it/) &#x20;

    Describes how Redux has some weaknesses with handling side effects and creating fractal applications, and how the Redux-Elm addon addresses those.
