# Vensy brand manager app

A react web app using redux and scss.
This project was created using create-react-app

## Prerequisites

1. Nodejs https://nodejs.org/en/
2. Npm or yarn

## Install project

1. Copy .env.example and rename the new file to .env
2. Change the .env contents according to your set up
3. Install the node packages

```
npm install // or yarn
```

## Run project

Starts a server on http://localhost:3000

```
npm run start // or yarn start
```

## Build project for production

This produces the relevant minified assets in the build folder.

```
npm run build // or yarn build
```

## Building svg sprite assets

We use svg icons in our app which we concatenate in a svg sprite,
To add or modify an icon, add/replace them in the "src/assets/svgs" folder as a single icon.
Then run the following command to build the sprite

```
npm run svg:sprite // or yarn svg:sprite
```

then you can use the icon by passing the filename of the svg to the Icon component


```
import Icon from "components/Icon";

<Icon variant={"action_add"} />
```
