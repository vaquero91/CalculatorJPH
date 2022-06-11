# Calculator

## Dev Notes
For this aplication we have an Angular project with a Calculator Component that contains the user interface were the client inputs the total trip price and then clicks the Send button to request the calculation, the component applies a basic data review and then calls the Calculator Service, where a API request is created using a prefab payload JSON that implements the cliend data. When the request is completed the result is publish on the Monthly Price field.

Note: the API Call is not completed so for the moment a hard coded 300 value is returned.

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.2.5.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.



