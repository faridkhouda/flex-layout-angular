# FlexLayout

Using flexbox CSS layout we can change the width and height of HTML DOM elements based upon the available space.

We can define different kinds of layouts for different kinds of display devices and different screen sizes.

Angular Flex Layout provides a sophisticated layout API using Flexbox CSS + mediaQuery. This module provides Angular developers with component layout features using a custom Layout API, mediaQuery observables, and injected DOM flexbox-2016 CSS stylings.

The Flex Layout engine intelligently automates the process of applying appropriate Flexbox CSS to browser view hierarchies. This automation also addresses many of the complexities and workarounds encountered with the traditional, manual, CSS-only application of box CSS.

The real power of Flex Layout, however, is its responsive engine. The Responsive API enables developers to easily specify different layouts, sizing, visibilities for different viewport sizes and display devices.

Getting Started
Start by installing the Angular Layout library from npm

npm i -s @angular/flex-layout @angular/cdk

Next, you'll need to import the Layout module in your app's module.

app.module.ts

import { FlexLayoutModule } from '@angular/flex-layout';
...

@NgModule({
    ...
    imports: [ FlexLayoutModule ],
    ...
});
After that is configured, you can use the Angular Layout attributes in your HTML tags for flex layout:




***********

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.4.


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
