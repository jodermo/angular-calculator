# AngularCalculator

 © 2019 - Moritz Petzka - <a href="https://petzka.com" target="_blank">petzka.com</a><br>
 <a href="mailto:info@petzka.com">info@petzka.com</a><br>

Demo:  <a href="http://calculator.petzka.com" target="_blank">calculator.petzka.com</a><br>


###Basic calculator component for Angular

component path:<br>
`src/app/calculator/..`

minimum options:<br>
`<app-calculator></app-calculator>`

 `[input]="value" `<br>
Start value for the calculator

 `(onUpdate)="callback($event)" `<br>
callback when some values changed

 `(onResult)="callback($event)" `<br>
callback when result button pressed

callback data `($event)`:<br>
 `{ `<br>
 `result: (numeric result value), `<br>
  `operators: [all calculation operators as array],`<br>
  `history: [calculation history as array] `<br>
   `}`

full example:<br>
 `<app-calculator [input]="inputValue" (onUpdate)="onUpdate($event);"  (onResult)="onResult($event);"></app-calculator>`










###This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.1.5.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
