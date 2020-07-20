# react-notes

## tools
- jsfiddle.net
- codesandbox.io
- react-devtools: this gives a react tab in developer console which matches the react code in our app which is useful for troubleshooting
- https://react-styleguidist.js.org/ for components
- https://storybook.js.org/  components
- https://www.styled-components.com CSS-in-JS styling for components (see Hands-on Web Development with React By Filip Danic)

## starter code
facebook's create-react-app gives us all the boilerplate, webpack, babel setup so that we can focus on writing the app.
$ npm install -g create-react-app # installs create-react-app cli to path
$ cd working-dir
$ create-react-app myproject
$ cd myproject
$ npm start # to start the dev server

index.js is the entrypoint rest of the files in starter code can be deleted

## redux
used for state management
- single store
- read only
- updated only by root reducer via a pure function
- components request to update state via actions, which are pure functions

$ npm install redux
