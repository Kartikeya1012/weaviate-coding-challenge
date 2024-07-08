For the Weaviate Coding Challenge, I chose to build a Pathfinding Visualizer App, using React JS.

# About the App

It is built with React JS, which visualizes Dijkstra's algorithm (pathfinding algorithm that guarantees the shortest path)

With this interactive app, with 2 fixed coordinates on a grid and walls that you can manually create, find the shortest path to that two points with a click of a button.

You can manually click and drag anywhere on the grid to create walls for the algorithm to avoid and navigate from.

## Preview of the project

Below is how the project will look like once you do `yarn start` or `npm start`. 

There is 2 fixed points - Green is the start node and Red is the end node

<img src="public/images/1.png" width=80% height=80%>

You can click and drag anywhere on nthe grid to create walls for the algorithm to avoid and navigate from.

<img src="public/images/2.png" width=80% height=80%>

To visualize the algorithm, click on the button at the top and the algorithm should work as below.

<img src="public/images/3.png" width=80% height=80%>

<img src="public/images/4.png" width=80% height=80%>

The yellow line show the shortest path with the Dijkstra's Algorithm.

<img src="public/images/5.png" width=80% height=80%>

## To Run this Project

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.<br>
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.
