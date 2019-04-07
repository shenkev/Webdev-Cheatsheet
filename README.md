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

[1]: Project name

```npx create-react-app [1]
```

## npm

Install a package
[1]: package

```npm install [1]```

### Ajax

```npm i -S axios
```

## Starting the servers

Front-end application

```npm start```

Back-end server

```node server.js```
