# True Alliance Front End Developer Tech Test Project

This project is used for testing the candidates' Front End development skills.

Your mission is to fix the issue and develop some features. We are also expecting from you a usable, responsive UI.

## Process

Please clone this project then create your own repository from it. Do not fork/branch this project when creating your solution as it will be visible to other applicants. Once your code is ready, please send us the link of your repository and we will review it. Please commit your work continuously. We prefer to see multiple commits rather than 1 giant commit.

## Getting Started

### Dependencies

* [Node JS](https://nodejs.org/en/) version v14.17.0 LTS
* [Yarn](https://yarnpkg.com/)

### Installing

* Clone this repository to your local
```
git clone git@github.com:truealliance/fedtechtest.git
```
* Run `cd fedtechtest` to enter project root directory
* Run `yarn` to install all of the local dependencies
* Run `yarn run build` to compile relevant files

### Executing program

* Run `yarn run js` to compile JavaScript files
* Run `yarn run css` to compile SCSS files
* Run `yarn run watch` to open a browser tab and watch the file changes (use port 8000 by default)
    * If `yarn run watch` is buggy, you can run `python -m SimpleHTTPServer 8000` to create a simple instance for testing

### Folder structure
```
* dist
    * css   // Compiled CSS files
    * img   // Compiled image files
    * js    // Compiled scripts
* node_modules
* src       // Source code
    * img   // Source images
    * js    // Source scripts
    * scss  // SCSS source files
        * components    // SCSS files for styling specific blocks or elements
        * utilities     // SCSS functions, mixins, placeholders
```
