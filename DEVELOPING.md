# Angular Sticky Things

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

Run `ng build angular-sticky-things --prod`

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

# Release
1. Start release: `git flow release start x.x.x`
1. Update versions
   1. ./projects/angular-sticky-things/package.json
   1. ./package.json
   1. update README.md
   1. Commit them (`chore(project): bump version to x.x.x`)
1. Changelog
   1. Generate `./node_modules/.bin/standard-changelog`
   1. Commit: `docs(changelog): update changelog for version x.x.x`
1. Finish release: `git flow release finish x.x.x`
1. Push: `git push --tags && git push origin develop:develop && git push origin master:master`
