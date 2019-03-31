# ng-hello-world
Hello World web app made with Angular 7.   
This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.3.7.

## Initialize
```
npm install -g @angular/cli
```
```
ng new a-hello-world
cd a-hello-world
ng serve --open --host 0.0.0.0
```

## Build and Deploy
```
npm install -g angular-cli-ghpages
```
```
ng build --prod --baseHref="https://johnveloper.github.io/ng-hello-world/"
ngh --dir=dist/a-hello-world
```