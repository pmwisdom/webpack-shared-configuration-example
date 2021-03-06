# Webpack shared configuration example

When you are working on multiple projects with similiar architecture it makes sense to have common configuration for dev tools like [Webpack](webpack.github.io), [Babel.js](https://babeljs.io) and etc.

This is an example of isomorphic React.js application using [Webpack](webpack.github.io), [Babel.js](https://babeljs.io), [webpack-isomorphic-tools](https://www.npmjs.com/package/webpack-isomorphic-tools) and [sass](http://sass-lang.com/).
 
Configurations are encapsulated by [webpack-tools](https://github.com/sergesemashko/webpack-tools), so packages are already pre-configured which allows you to:
 
- save time on configuring webpack, babel.js, etc. and start development right away
- version your webpack configuration and choose certain config from NPM dependencies
- keep your favorite webpack configuration in sync on multiple projects


**IMPORTANT NOTE:** make sure you are using [NPM](www.npmjs.com) **2.x.x**, it may not working properly with **3.x.x** 

## Install

1. `npm install`
2. 1) `npm run dev` to start dev server or 2) `npm run start` to start server using production config
