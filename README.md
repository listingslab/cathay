# Boilerplate SPA in React

React Front End Framework with Redux, Firebase, Sass, MUI & more. forked from columbus-front-end 2018_05_29 at version 0.6.10

At this point the Columbus project has laid a framework which can be easity followed and reused as a template to bootstrap a new PWA for the product's ecosystem.

__Why Cathay?__

When Christopher Columbus headed West, he wasn't thinking of discovering America. 
He was looking for Cathay.

## Installation

```bash
cd <project-path>
yarn
```
Assume all commands are to be executed from the project's root directory.

## Firebase

If you wish to use Firebase, set up a new project in the Firestore Console. and grab the config details which will look something like this:

```javascript
const config = {
	apiKey: "AIzaSyB6i0juorvEHhTJJ42J5bSpP0E3UH5xN1Y",
	authDomain: "cathay-df6d0.firebaseapp.com",
	databaseURL: "https://cathay-df6d0.firebaseio.com",
	projectId: "cathay-df6d0",
	storageBucket: "cathay-df6d0.appspot.com",
	messagingSenderId: "353287349232"
};
```

## Node Quick-Scripts

These are the scripts that you can run  `npm run <script-name>` or `yarn <script-name>`.

- start
- build
- deploy
- lint
- test
- deploy-to-jenkins-on-azur
