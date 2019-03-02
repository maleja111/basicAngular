# BasicAngular

## Check your Angular Cli version
- Confirm if you already have installed Angular 6 or <
`ng -v`
- Confirm if you already have installed Angular 7
`ng version`

## Install Angular cli
- Installed globally in your system with "-g" 
`npm install -g @angular/cli@latest`

## Update Angular cli
- If you need Update 
`ng update @angular/cli @angular/core`

- You can verify if you have the 7 version
 `ng version`

 ## Create a New Project
- Create your project 
`ng new basicAngular`

- Configure this options
![](/src/assets/images/install-options.png)

- start service, Navigate to `http://localhost:4200/`.
`ng serve`

 ## Notes

- If you have this error `node_modules/rxjs/internal/types.d.ts(81,44): error TS1005: ';' expected error after installation of Angular 6`
- *Step 1* : Go to package.json and modify "rxjs": "^6.0.0" to "rxjs": "6.0.0"
- *Step 2* `Run npm update` in your project.
- If you need Install 
`npm cache verify`
- Start service.
`ng serve` 

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
