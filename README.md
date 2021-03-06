# Todo React Client with Express API

## Express

#### Resources

* [Express](https://expressjs.com/)
* [Express application generator](https://expressjs.com/en/starter/generator.html)
* [Knex](https://knexjs.org/)
* [Knex: Cheat Sheet](https://devhints.io/knex)
* [npm: cors](https://www.npmjs.com/package/cors)

## React

### Todo App Client with React and Materialize

#### How to set up a basic React App from create-react-app and add react-materialize

1. Use create-react-app to create todoclient, cd into directory, and install dependencies.
```bash
$ create-react-app todoclient
$ cd todoclient
$ yarn start
```
2. Delete contents of public and src folders.
3. Create an index.html file in public
```html
<!doctype html>
<html>
  <head>
    <title>Todo Client</title>
  </head>
  <body>
    <div id="root"></div>
  </body>
</html>
```
4. Create an index.js in the src folder
```js
import React from 'react';
import ReactDOM from 'react-dom';

ReactDOM.render(<div><h1>My Amazing Todo App</h1></div>, document.getElementById('root'));
```
5. Add some style! Install react-materialize.
```bash
$ yarn add react-materialize
```
Import Google Icon Font and materialize.css into public/index.html
```html
<head>
  <!-- Import Google Icon Font -->
  <link href="http://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
  <!-- Import materialize.css -->
  <link href="https://cdnjs.cloudflare.com/ajax/libs/materialize/0.98.0/css/materialize.min.css" rel="stylesheet">
</head>
```

#### Resources

* [React](https://reactjs.org/)
* [React Docs: AJAX and APIs](https://reactjs.org/docs/faq-ajax.html)
* [Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API)

## Spotify API

### Authentication

![Authorization](https://developer.spotify.com/assets/AuthG_AuthoriztionCode.png "Logo Title Text 1")


#### Resources

* [Spotify Web API](https://developer.spotify.com/documentation/web-api/)
* [Spotify Authorization Guide](https://developer.spotify.com/documentation/general/guides/authorization-guide/)
* [Spotify Web Authorization Example](https://github.com/spotify/web-api-auth-examples/tree/master/authorization_code)
* [A client-side JS wrapper for the Spotify Web API](https://github.com/jmperez/spotify-web-api-js)
