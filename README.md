# Three FPS Demo

Three.js FPS game using ammo.js and three-pathfinding with ES6 and Webpack.

The project features an entity/component system, FPS controller using ammo.js rigidbody, NPC with root-motion animations and a basic AI.

Please note that the project is still under development.

## Install
Before you begin, make sure you are comfortable with terminal commands and have [Node and NPM installed](https://www.npmjs.com/get-npm). Then either install via a download or with Git.

### Install via Download
In terminal at that folder type `npm install` to set things up. To get going run: `npm start`.

## Running the development server
To see the changes you make to the project go to the project's folder in terminal and type...

```bash
npm start
```

This command will bundle the project code and start a development server at [http://localhost:8080/](http://localhost:8080/). Visit this in your web browser.

## Editing the code
The first file you should open is `./src/entry.js`. In it you will find the main application class. This class is reponsible for initializing the libraries and loading art assets, it also handles the main game loop.

## Building the project for the web
Running `npm run build` in terminal will bundle your project into the folder `./build/`. You can upload this directory to a web server. For more complex results read [this guide](https://webpack.js.org/guides/production/).

## About the models
Art assets used in this project:

* [Ak47](https://skfb.ly/6UEL9) by [kursat_sokmen](https://sketchfab.com/kursat_sokmen) is licensed under CC BY 4.0
* [Metal Ammo Box](https://skfb.ly/6UAQY) by [TheoClarke](https://sketchfab.com/TheoClarke) is licensed under CC BY 4.0
* [Mutant](https://mixamo.com) by [mixamo.com](https://mixamo.com)
* [Veld Fire](https://hdrihaven.com/hdri/?h=veld_fire) by [Greg Zaal](https://hdrihaven.com/hdris/?a=Greg%20Zaal) is licensed under CC0
