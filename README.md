## Initialize
```
npm install -g @angular/cli
```
```
ng new ha-ello-world
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