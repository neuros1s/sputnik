Starter app built with angular2 based on angular2 5 min Quickstart (https://angular.io/docs/ts/latest/quickstart.html).

##Features

* browsersync for autorealod
* sass preprocessor for app styling

##Scripts

### App runs

* npm start - runs the compiler and a server at the same time, both in "watch mode"

* npm run tsc - runs the TypeScript compiler once

* npm run tsc:w - runs the TypeScript compiler in watch mode; the process keeps running, awaiting changes to TypeScript files and recompiling when it sees them

* npm run lite - runs the lite-server, a light-weight, static file server with excellent support for Angular apps that use routing

* npm run typings - runs the typings tool separately

* npm run postinstall - called by npm automatically after it successfully completes package installation. This script installs the TypeScript definition files defined in typings.json

### Styles

* npm run sass - compile ./app/sass/app.scss and copy it to ./assets/css

* npm run sass:production - compile and with postcss compress ./app/sass/app.scss and copy it to ./assets/css

* npm run sass:watch - run sass in "watch mode" and postcss on change any ./app/**/*.scss file

##Installation

* clone the repository
* go to sputnik dir and run: npm install
* npm run sass
* npm start

Enjoy and feel free to fork and improve :)