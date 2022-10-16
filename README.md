# nfs-web
Évaluation orchestration de conteneurs - Partie ReactNative


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

## Available Scripts for Docker

In the project directory, you can run:

### `docker build -t <image name> .`

Creates a docker image for the application.

### `docker run -d —name <container name> -p 3000:3000 <image name>`

Launches the application container.\
You have access to the application on port 3000 of your computer.


#### Exemple : 
`docker build -t nfs-web .` \
`docker run -d —name  nfs-web-container -p 3000:3000 nfs-web`
