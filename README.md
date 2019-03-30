## Initialize
```
npm install -g @angular/cli
```
```
ng new hello-world
cd hello-world
ng serve --open --host 0.0.0.0
```

## Build and Deploy
```
npm install -g angular-cli-ghpages
```
```
ng build --prod --base-ref="https://USERNAME.github.io/REPONAME/"
ngh --dir=dist/PROJECTNAME
```