[[TOC]]

# Descriptions

This project user ```ReactJS``` with [Redux](https://redux.js.org/) and [Axios](https://axios-http.com/docs/intro) library to build the user view
 of Permit
 application

To understand this project you must read about [ReactJS](https://reactjs.org/). For more information, see some key file
 and folder below:

|File/Folder|Description|Note|
|----|----|----|
|.env|store all project's config like database, service url ...|Make sure all config only connect to your local or develop environment|
|./package.json|This file allow we sharing packages information using in this project.|This is required file, **DO NOT DELETE**|
|./src/views|This folder store all app screen|| 
|./src/redux|This folder store redux setting to interaction between components|| 
|./src/api|This folder store all api class to connect with backend server||
|./src/components|This folder store all react components||

# Tech required

|Tech|Version|Link|
|----|----|----|
|NodeJS|14.17.0|[dowload](https://nodejs.org/en/download/)|
|NVM|lasted|[install guide](https://github.com/coreybutler/nvm-windows#installation--upgrades)|

# Setup

 1. Install dependencies
 1. Switch to correct node version
 1. Build project
 1. Start project

## Install dependencies

Run glide command to install all dependencies have been defined on ```package.json```
```bash
npm install
```

## Switch to correct node version

The project is work stable on Node version ```14.17.0```, so web need to change the NodeJS version

Download NodeJS 14.17.0
```bash
nvm download 14.17.0
```
Use this version after download done
```bash
nvm use 14.17.0
```
Show Node version to sure is work
```bash
node -v
```

## Build project

```bash
npm run build
```

# Start project

To success build and run project to must turn on windows defender 

```bash
npm start
```

# Error on build or start project

In case fail on build or start project with list error below

- 'react-app-rewired' is not recognized
- Maximum call stack size exceeded

Run these commands to fix

```bash
npm cache clean --force
npm rebuild
npm install
```
