# Basic Desktop App with React and Electron 

This project is a base for making a desktop app using React and Electron for a responsive app.

It's based in the tutorial made by [Devesu](https://medium.com/@devesu/how-to-build-a-react-based-electron-app-d0f27413f17f).

## Requirements

This project is made in a ambient with `Node 14.16.0` and `npm 6.14.11`. It uses a bunch of dependencies that are necessary to:

- Run React and Electron simultaneously during development
- Build the window frame
- Make the final Build of the app

Extra Modules and Dependencies are managed in the `packaje.json` file.

## How to use

After clonning the project, run `npm install` to install required dependencies.

- For developing the React Page, use `npm run react-start`
- For testing the Electron App, use `npm start`


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs concurrently the React Page and the Electron App in development mode.\
It's possible to acess the React page in the local browser in [http://localhost:3000](http://localhost:3000).

### `npm run build`

Builds the React app for production to the `build` folder, and uses the result to build the Electron app for production to the `dist` folder, including a `.exe` for installation. 

### `npm run react-start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm run react-test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run react-build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!