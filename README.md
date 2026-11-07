# Angular app with Angular Material

Source code used in the article [Install Angular Material in an Angular project](https://blouppy.com/blog/2023-01-01-install-angular-material-in-an-angular-project/) on the [Blouppy](https://blouppy.com) website.

It is the welcome page `ng new` generates, with Angular Material added by `ng add @angular/material`
(Material 3 theme with the Azure/Blue palettes in `src/styles.scss`) and one Material button,
`<button matButton="filled">`, imported as a standalone directive in `src/app/app.ts`.

## Project type

- Angular project: standalone components, signals, zoneless change detection, no `NgModule`.

## Project version

- Angular 22. This project was generated with [Angular CLI](https://angular.dev/tools/cli) version 22.2.6.
- Node.js 22 (an active or maintenance LTS version is required).

## NPM packages included

- **@angular/material**: 22.2.6
- **@angular/cdk**: 22.2.6

## Run it

```bash
npm ci
npm start                 # ng serve, then open http://localhost:4200/
npm run build             # production build in dist/
npx ng test --watch=false # unit tests (Vitest)
```

## Give a Star! :star:

If you like or are using this project please give it a star. Thanks!

## Support this project! :pray:

If you want to help me to maintain this project or add improvements, it would be a pleasure!
