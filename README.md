# typescript-es6-babel-webpack
Starter to compile typescript es6 output with babel

According to [https://github.com/Microsoft/TypeScript/wiki/What's-new-in-TypeScript](https://github.com/Microsoft/TypeScript/wiki/What's-new-in-TypeScript) and [http://kangax.github.io/compat-table/es6/](http://kangax.github.io/compat-table/es6/)
TypeScript supports a number of really cool language features, but only if you have ES6 as the compilation target for the TypeScript
compiler. Among them are iterators, for..of, Maps and the spread operator (...). 

In order to make the compiled code run in all browsers, we chain together babel and TypeScript loader using webpack. This effectively produces ES5 from all TypeScript code. Even source maps work.
