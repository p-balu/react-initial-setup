### Latest version of NODEJS is needed to run this file

### Initally run 
`npm install` or `yarn` this will install all the packages in package.json
 
 "npm install or yarn" installs packages like
 react,react-router-dom,babel,webpack-cli, html-webpack and css loader packages.
 
 #### After npm install or yarn we need to configure webpack.config.js
 
 ### After configuring webpack 
 create `.babelrc` and add babel presets and plugins i.e. the piece of code that is given below
 
 {
  "presets": ["@babel/preset-react"],
  "plugins": ["@babel/plugin-proposal-class-properties"]
}

### Finally run the application using `npm start`
