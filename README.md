# Express with ES6

An skeleton express app that allows you to use ES6 syntax. Generated by express-generator cli.

## How to run

Before anything else, you must have node installed on your machine.

Install packages with `yarn install`

### Running Dev Server

Run on your terminal `yarn watch:dev`, the server will restart everytime you make a change in your code.

### Running Dev Server on Windows

If you encounter issues with starting the local dev environment, you will want to install winn-node-env.
Just run, `npm install --save-optional win-node-env` then `yarn watch:dev`

### Running Production Server

For stuff like heroku deployment, aws elasticbeanstalk, run `npm run start`

### Other scripts

* `transpile` - convert es6 and beyond code to es5 to a folder named `dist-server`
* `clean` - delete transpiled folder
* `build` - clean and transpile
