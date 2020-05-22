# React_Webpack
  This project provides a react teamplate created from scratch to provide support like JS bundling using webpack, babel transpiling for devlopement and hot reloading etc.
## Steps to start project
  - npm i (to fetch npm dev dependencies)
  - npm start (run react in localhost)
  - npm run build (create JS bundle using webpack)
### dist folder is also checked in to test JS bundle independently in Html files 

## Notes
- npm init (To create package.json)
- npm i react react-dom 
- npm i --save-dev webpack webpack-dev-server webpack-cli  
- npm i @babel/core babel-loader @babel/preset-env @babel/preset-react --save-dev
- npm i --save-dev html-webpack-plugin

Files created:
- webpack.config.js
- .babelrc
	{
    "presets": ["@babel/preset-env", "@babel/preset-react"]
	}
- HTML template: index.html

Dependencies:
- react
- react-dom

Dev Dependencies:
- babel-core
- babel-loader
- babel-preset-env
- babel-preset-react
- webpack
- webpack-cli
- webpack-dev-server
- html-webpack-plugin

