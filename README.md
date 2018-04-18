# AngularFiveCoursetro

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.7.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
---

# angular-five-coursetro

## install node js
```
sudo apt-get update
```
[Install nodejs via package manager](https://nodejs.org/en/download/package-manager/)

verify the instalation
```
nodejs -v
v8.11.1
```
Using this instalation Node Package Manger is set up as a
dependency so should be allready installed

## install angular
install angular globaly
```
sudo npm uninstall -g @angular/cli
sudo npm install -g @angular/cli
```
## create a project
```
ng new angular-five-coursetro --style=scss --routing
```
## usefull commands
```
ng generate component home
ng g c about
```

### annimation
```
npm install @angular/animations@latest --save
```

### deploy to github pages
```
ng build --prod --base-href="https://bogdan-marian.github.io/angular-five-coursetro/"

angular-cli-ghpages
```

just a refference in case ```angular-cli-ghpages``` failes: ([comand files](https://github.com/angular-schule/angular-cli-ghpages/issues/9))