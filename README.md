# mbta-stop-display-updated

# 🚀 TransitFind is an MBTA line/stop information web app for dedicated displays. 🚀

https://github.com/coding-to-music/mbta-stop-display-updated

From / By https://github.com/jprusik/mbta-stop-display

https://jprusik.github.io/mbta-stop-display/

https://transitfind.com/

## Environment variables:

```java
REACT_APP_API_KEY=

# value in milliseconds
REACT_APP_PREDICTIONS_REFETCH_INTERVAL=10000

REACT_APP_GA_ID=
```

## GitHub

```java
git init
git add .
git remote remove origin
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:coding-to-music/mbta-stop-display-updated.git
git push -u origin main
```

## typical start

```
cp .env.example .env

Register for a google tag 

https://tagmanager.google.com/#/home

https://tagmanager.google.com/?authuser=0#/home

https://support.google.com/google-ads/answer/11994839?sjid=10442131574757201905-NA

modify .env

yarn install
yarn build

Open port 3000

yarn start
```

# TransitFind

TransitFind is an MBTA line/stop information web app for dedicated displays.

See the app in action: [https://transitfind.com](transitfind.com)

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Getting started

Upon build, the app expects to find a dotfile (named `.env`) with environment variables in the project's root directory. See `.env.example` for sample values an additional explanations.

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

