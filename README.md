# pagebone
:fire: :package: A minimal Boilerplate to create new projects using Parcel, beside another technologies such as SASS and ES6 with Babel

This project uses Parcel with SASS and Babel to transpile es6+ to es5

Maybe you want to read about them:
- [Babel](https://babeljs.io/)
- [Sass](http://sass-lang.com/)
- [Parcel](https://parceljs.org/)

### Installation

First of all, install the dependencies to run this project.

- [NodeJS](http://nodejs.org/)

```sh
# Clone this repository
$ git clone https://github.com/jrstylle/pagebone.git
$ cd pagebone

# install dependencies
$ npm install
```
With the commands above, you have everything to start.

```sh
├── src
│   ├── scripts/
│   │   └── index.js
│   ├── styles/
│   │   └── index.scss
├── .babelrc
├── .editorconfig
├── .eslintrc
├── .gitignore
├── index.html
├── package.json
```

Those folders and file may change during the project development.

### Code Standards
This project uses [ESlint](http://eslint.org/) and [.editorconfig](https://github.com/jrstylle/pagebone/blob/master/.editorconfig) is defined to have indent_size of **2 spaces**.


### Tasks
`npm start`: run the Parcel to initialize a local server and watch for changes in the files

`npm build`: run the Parcel to generate build package

