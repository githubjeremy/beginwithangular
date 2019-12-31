# Begin With Angular -- Starter Project

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.5.

This is a starter pack for angular

* Firstly, in order to build the TypeScript compiler, ensure that you have [Git](https://git-scm.com/downloads) and [Node.js](https://nodejs.org/) installed.you have to download the last version of LTS from [Node.js](https://nodejs.org/)

* Then, install NPM package and ANGULAR/CLI :

```bash
npm install -g npm@latest
npm install -g @angular/cli
```

* Create the project with the commande as follow  with or without tests :

```bash
ng new projectname
ng new projectname --skip-tests=true
```
## Clone the repository

If you want clone a copy of the repository :

```bash
git clone https://github.com/githubjeremy/beginwithangular.git
```

## Bootstrap

You have the possibility to install bootstrap and all dependences that you want :
```bash
npm install bootstrap@versionnumber --save
```
After running the previous commande add this follow line in the styles of angular.json :
```bash
"styles": [
    "node_modules/bootstrap/dist/css/bootstrap.css",
    "src/styles.scss"
],
```

## Development server

Run `ng serve` for a dev server.
```bash
ng serve --o
```
Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component.
```bash
ng g c componentName
```
You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project.
```bash
ng build
```
The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).
```bash
ng test
```

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
```bash
ng e2e
```

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
```bash
ng help
```