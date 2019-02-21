# recastly-redux
This is a project I completed as a student at [hackreactor](http://hackreactor.com). This project was worked on with a pair.

From our previous sprint, we now have a simple yet functional React application hooked up to live YouTube data. This is spectacular, and now it's time to consider adding features to our application. But as we plan, more features turn into more components, handlers must be passed further up and down the component tree, or sometimes from laterally across our app... yikes! This is getting prohibitively complex very quickly!

One popular solution to the problem of increased complexity is flux design. This paradigm stresses a single state object as the sole "source of truth" for your application, and defines all user actions as changes to that state. Actions themselves are simply objects (or, if we are using Redux Thunk, functions), which must pass through a reducer function which defines how each action alters the state. In this sprint, we will walk through the process of converting our codebase to use Redux, a flux implementation that works very well with React.

We have collected some useful resources, which you are encouraged to consult.

