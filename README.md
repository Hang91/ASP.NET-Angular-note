# ASP.NET-Angular-note

## Error1:
Error: Could not find an NgModule for the new component. Use the skip-import option to skip importing components in NgModule.

solution:

ng g c header --module='app.module.browser.ts'

## Error2:
input.mergeMap is not a function

solution:

1.remove the local angular cli by: npm remove @angular/cli --save

2.install global angular cli by: npm install -g @angular/cli@latest

## development mode
check the website:
https://docs.microsoft.com/en-us/aspnet/core/fundamentals/environments


## Error
```json
  "include": [
    "src/**/*",
    "node_modules/angular-xyy/index.ts"
  ]
```
