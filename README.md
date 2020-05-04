# our-fb-app
Extends create react app to include Firebase, authentication, Authorization and all reusable components

This App Generator will eventually avoid having to create Authentication/Authorization and other reused mechanisms over and over when starting a new React App. 

### Creating an App – How to create a new app.
User Guide – How to develop apps bootstrapped with Create React App.
Create React App works on macOS, Windows, and Linux.
If something doesn’t work, please file an issue.
If you have questions or need help, please ask in our Spectrum community.

Quick Overview
```bash
npx create-ourfb-app my-app
cd my-app
npm start
```

Then open http://localhost:3000/ to see your app.
When you’re ready to deploy to production, create a minified bundle with npm run build.

```bash
npm start
```

Get Started Immediately
You don’t need to install or configure tools like webpack or Babel.
They are preconfigured and hidden so that you can focus on the code.

Create a project, and you’re good to go.

Creating an App
You’ll need to have Node 8.16.0 or Node 10.16.0 or later version on your local development machine (but it’s not required on the server). You can use nvm (macOS/Linux) or nvm-windows to switch Node versions between different projects.

To create a new app, you may choose one of the following methods:

npx
```bash
npx create-react-app my-app
```
(npx is a package runner tool that comes with npm 5.2+ and higher, see instructions for older npm versions)

It will create a directory called my-app inside the current folder.
Inside that directory, it will generate the initial project structure and install the transitive dependencies:

```bash
my-app
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── public
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
└── src
    ├── api
    │   └── firebase.js
    ├── store
    │   ├── Action.js
    │   ├── data.js
    │   ├── db.js
    │   ├── index.js
    │   └── StoreReducer.js
    ├── components
    ├── utils
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.css
    ├── index.js
    ├── logo.svg
    └── serviceWorker.js
    └── setupTests.js
```
Once the installation is done, you can open your project folder:

```bash
cd my-app
```

Inside the newly created project, you can run some built-in commands:

npm start or yarn start
Runs the app in development mode.
Open http://localhost:3000 to view it in the browser.

The page will automatically reload if you make changes to the code.
You will see the build errors and lint warnings in the console.

npm run build or yarn build
Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.

Your app is ready to be deployed.
