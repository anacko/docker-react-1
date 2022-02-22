# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

Following the steps provided [here](https://medium.com/sliit-foss/dockerizing-a-react-js-app-fbe84f214d7e) - with adaptations. (pdf with annotations in the docs folder)

## React
`npm start` to run the project in develpment mode (`localhost:3000`)
`npm run build` for the production version.

## Docker
`docker build -t <folder-name> .` to build the image
`docker run -p 3000:80 <folder-name>` to run (`localhost:3000`)