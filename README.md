# Getting Started with Create React App: BE SURE TO HAVE NODE AND NPX, NPM, or YARN INSTALLED IN ORDER TO RUN REACT
Creating an App!!!
You’ll need to have Node 10.16.0 or later version on your local development machine (but it’s not required on the server). We recommend using the latest LTS version. You can use nvm (macOS/Linux) or nvm-windows to switch Node versions between different projects.

To create a new app, you may choose one of the following methods:

NPX:
--
npx create-react-app my-app
(npx is a package runner tool that comes with npm 5.2+ and higher, see instructions for older npm versions)

NPM:
--
npm init react-app my-app
npm init <initializer> is available in npm 6+

YARN:
--
yarn create react-app my-app
yarn create <starter-kit-package> is available in Yarn 0.25+

It will create a directory called my-app inside the current folder.
Inside that directory, it will generate the initial project structure and install the transitive dependencies:

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
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.css
    ├── index.js
    ├── logo.svg
    └── serviceWorker.js
    └── setupTests.js
No configuration or complicated folder structures, only the files you need to build your app.
Once the installation is done, you can open your project folder:

cd my-app
Inside the newly created project, you can run some built-in commands:

npm start or yarn start
Runs the app in development mode.
Open http://localhost:3000 to view it in the browser.

------------------------------------------------------------------------------------------------------------------------------------
In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

