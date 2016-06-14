#Why redux?

Redux centralizes all of your application state in one store. Inn fact, it enforces keeping all state in a single centralized object graph. This makes the app easier to understand, and avoids the complexity of handling interactions between multiple stores.

Redux requires less boilerplate code than Facebook's Flux pattern. Your top level container component subscribe to the Redux store in a very elegant way.

Redux has an immutable store, which has a number of benefits, including performance.

Redux also enables interesting features like Hot Reloading, which means that you can instaltly see changes in your browser without losing your current client-side state, Time-travel debugging, which allows you to step forward and backward though state changes in your code, and even replay interactions

Redux has a small API (2kb)

#DevDependencies

Babel transpiles JavaScript ES6's new syntax to ES5 so it can run in the browser

Webpack has become the most popular bundler in the React community, because it's extremely powerful and extensible. I used webpack to bundle the compiled javascript in a signle minified file which works in the browser

For testing we're going to use Mocha, which is the most popular JavaScript testing framework out there

ESLint is a tool to lint our javascript code and it will alert us when we make mistakes in our code