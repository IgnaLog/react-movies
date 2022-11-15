# OMDB Movie React App

This application belongs to the set of tutorials made with React.

Made with class components.

It consists of displaying a set of movies extracted from the [OMDB API](https://www.omdbapi.com/) based on a search.

![Alt Text](https://media.giphy.com/media/mLdxgm7swIP6Q6ZQBt/giphy.gif)

This project was bootstrapped with [webpack](https://webpack.js.org/) and [babel](https://babeljs.io/) to interpret code. Also use [eslint](https://eslint.org/) to prevent errors.

## OMDB API

You will need a key for the [omdb API](https://www.omdbapi.com/). 
You will get it by registering at: [https://www.omdbapi.com/apikey.aspx](https://www.omdbapi.com/apikey.aspx).
Afterwards create a .env file in the main project directory. 
Copy there the address of the API with its APIKey at the end of the url:

    API=https://www.omdbapi.com/?i=txxxx61x8&apikey=xxxxxxxx

## Node Modules

This app uses some modules like:

    npm i dotenv-webpack
    npm i prop-types 
    npm i eslint eslint-loader eslint-plugin-react
    npm i css-loader style-loader
    npm i bootswatch 
    npm i webpack webpack-cli @babel/core @babel/preset-env @babel/preset-react babel-loader -D
    npm i webpack-dev-server
    npm i react react-dom
    npm i html-webpack-plugin

To load them just use:

### `npm install`

They will be loaded from package.json dependencies.

## Available Scripts

In the project directory, you can run:

### `npm start`


Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm run production`

Builds the app for production to the `dist` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).