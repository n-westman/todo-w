
// ====================================  
// NOTES  
// ====================================  

ToDo App	
Notes and progress.
	
    1. I created a react structure app by using create-react-app “name of app”.
  
    2. I initiated a git repository that now is live on n-westman GitHub. (here)
	Reminder to git add // git commit // git push to add updates to the repository.

	3. I made a structure to get started with Sass using React by creating inside 
    the src foldertwo new folders named “sass” & “css”. Added a style.scss inside 
    sass folder aswell as added the folders “component”, “base”, “style” and 
    “utilities”. Then inside utilities I create “_functions.scss”, “_helpers.scss”, 
    “_mixins.scss” and “_variables.scss”. (Based on structure from treehouse lesson).

	4. I initiated the sass watch in terminal with “sass --watch scss:css” which created a 
	“style.css” & “style.css.map”.  I then linked the new “style.css” to App.js so everything 
    is 	set up. Also testing it on the main App component to se that a variable goes through 
    scss, compiles and results in css in the results with the className=“test”.	
    
    5. Basstrukturen är skapad. Adderas componenterna TodoItems och TodoList som skickar 
    information till App componenten. Css bas har tagits fram med hjälp av Sass men ännu
    inte använt Sass "enkelhet" fullt ut än. 

    6. Nästa steg är att strukturera upp Sass i olika mappar samt kunna ta bort TodoItems.

// ====================================  
// CREATE-REACT-APP BASIC INFO      
// ====================================  

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br />
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.<br />
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.<br />
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br />
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (Webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: https://facebook.github.io/create-react-app/docs/code-splitting

### Analyzing the Bundle Size

This section has moved here: https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size

### Making a Progressive Web App

This section has moved here: https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app

### Advanced Configuration

This section has moved here: https://facebook.github.io/create-react-app/docs/advanced-configuration

### Deployment

This section has moved here: https://facebook.github.io/create-react-app/docs/deployment

### `npm run build` fails to minify

This section has moved here: https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify
