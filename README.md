# Webdev-Cheatsheet

## Overview

npm: manages all packages including react, express
node: compiles code
react: front-end javascript functionality
express: catches requests from front-end, connecting them to the back-end
mongodb: database


You essentially build two independent apps. With express and mongodb, you have a backend app that receives requests. With react, you build a front-end app that executes javascript to provide the user experience.

## Setup

### Node

It's better to use a node package manager incase you want to update node in the future.

Install nvm

```
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.34.0/install.sh | bash
```

Install node

```nvm install node```


### Initialize a project

The create-react-app library takes care of all the unsexy work in setting up the development environment with React and other libraries, as well as building.


Look at https://github.com/facebook/create-react-app#whats-included for reference for setup and building in production.
For a summary of what create-react-app does https://stackoverflow.com/questions/50722133/what-exactly-is-the-react-scripts-start-command

[1]: Project name

```npx create-react-app [1]
```

## npm

Install a package
[1]: package

```npm install [1]```

### Libraries
axios: let's you make ajax requests to backend
morgan: prints the GET /api/getData 304 42.429 ms - - in console
bodyParser: turns raw http request message into javascript object
cors: security for which backend servers can talk to which front-end apps
nodemon: watches your files and restarts server when they change

## Starting the servers

Front-end application

```npm start```

Back-end server

```node server.js```
