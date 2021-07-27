# pokedex-typescript
Pokedex with PostGreSQL done in TypeScript/Express

# Goals for this repo:
Create an application that allows users to display a dynamic list of Pokemon, filter by type, and edit/create new Pokemon.

# Implement the functionality detailed in the following steps:

# Step 1
Build out an express server to serve the front end. Create a script for starting the server and for webpack. Refactor your client to dynamically render from your React files. You will know if you have done this correctly if you see Bulbasaur, Ivysaur, and Venasaur on the page.

# Step 2
Using mysql, build out the back-end. Use schema.sql to create and seed the "pokedex" database. Establish a database connection in db/index.js

# Step 3
Create a GET route to display all the Pokemon in your database onto the page. You should render each Pokemon's name, type, and image. Refactor the hardcoded select dropdown menu to display all of the types stored in the database. Filter the displayed Pokemon to match the type selected in the dropdown menu. Re-display all the Pokemon on the page when 'Show All' is clicked.

# Step 4
On click of the Pokemon's name, enable editing through an input field. On 'submit', your component should re-render so the updated name is displayed.

Create a delete button to delete a Pokemon. On click of the delete button, the Pokemon should be removed from the page.

# Stretch Goal
Implement an 'Insert' button and corresponding POST route so you can add a Pokemon to the list.

# Requirements
Make sure to add comments for readability and for new engineers to understand the stack. Don't want to come back to it in a few weeks and not have any idea what's going on.

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

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

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
