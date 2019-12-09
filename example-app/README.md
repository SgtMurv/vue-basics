# frontend
This folder contains a Vue Project created with the [@vue/cli](https://cli.vuejs.org/). This folder contains all of the code to do with the development of the frontend of the zero-waste application.

## /public
This folder contains the [HTML file]('/../public/index.html') which the Vue code is injected into when the  project gets built.

## /src
This folder contains all of the source Vue code that is written. The vue instance is initiated in [main.js]('/../src/main.js'). All of the frontend is comprised of components that are made up of HTML, CSS and JavaScript. These components are located in [/components]('/src/components'). All of the assets in the application including images, svgs and any css/ scss are stored in the [/assets]('../src/assets') folder.

## package.json & package-lock.json
These files are to do with keeping track of the dependencies of the application. The node-modules folder is not pushed up to the repository as when the repo is pulled then you can just run:
```
npm install
```
This will go through the package-lock.json file and install all dependencies that are not present in the application.

## babel.config.js
[Babel](https://babeljs.io/) is a wonderful invention that allows us developers to write modern javascript that will work across mutliple browsers. This config file is automatically created with the vue project. I can only assume it has something to do with converting the javascript we write in this vue project into browser friendly javascript.

## .gitignore
This magical file tells git to ignore whatever files we declare within it with the syntax of:
```
filename
/foldername
```