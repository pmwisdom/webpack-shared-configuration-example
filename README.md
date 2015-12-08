# Webpack shared configuration example

When you are working on multiple projects with similiar architecture it makes sense to have common configuration for dev tools like [Webpack](webpack.github.io), [Babel.js](https://babeljs.io) and etc.
This is an example of isomorphic React.js application using [Webpack](webpack.github.io), [Babel.js](https://babeljs.io), [webpack-isomorphic-tools](https://www.npmjs.com/package/webpack-isomorphic-tools) and [sass](http://sass-lang.com/). 
Webpack and babel configurations are encapsulated by [webpack-tools](https://github.com/sergesemashko/webpack-tools), so you just use pre-configured Webpack and Babel which allows you to:
 
- save time on configuring webpack and start development right away
- version your webpack configuration and choose certain config in npm dependencies
- keep your favorite webpack configuration in sync on multiple projects


**IMPORTANT NOTE:** make sure you are using [NPM](www.npmjs.com) **2.x.x**, it may not working properly on **3.x.x** 

## Install

1. `npm install`
2. `npm run dev` to execute webpack using dev config
Or you can run
2.2 `npm run start` to run webpack build and run server for producation
