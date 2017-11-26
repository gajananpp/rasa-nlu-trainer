# rasa-nlu-trainer-with-typo

[![NPM](https://nodei.co/npm/rasa-nlu-trainer-with-typo.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/rasa-nlu-trainer-with-typo/)

This is a tool to edit your training examples for [rasa NLU](https://github.com/rasahq/rasa_nlu)


[install with npm](#installation)

## installation

`$ npm i -g rasa-nlu-trainer-with-typo` (you'll need [nodejs and npm](https://nodejs.org/) for this)

## launch
`$ rasa-nlu-trainer-with-typo` in your working directory

this will open the editor in your browser

#### options
- `--source -s` path to the training file (by default it will be searched recursively in the current directory)
- `--port -p` the web app will run here (randomly selected by default)

## development

- git clone this repo
- `$ npm install`
- `$ npm start`

#### using the development build locally

- `$ npm run build`
- `$ npm link`

from here, the `$ rasa-nlu-trainer-with-typo` command will start the development version

run `$ npm run build` again to update the build

run `$ npm unlink && npm i -g rasa-nlu-trainer-with-typo` to use the npm version again


This project was bootstrapped with [Create React App](./CRA_README.md).
