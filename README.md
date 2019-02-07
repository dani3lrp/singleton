# Singleton

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 7.0.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

### bitácora
## día 1

#ng new singleton --routing
----------------------------------------------------------------
----------------------------------------------------------------
app.module.ts
----------------------------------------------------------------
import { LOCALE_ID, NgModule } from '@angular/core';

//configurar español
import { registerLocaleData } from '@angular/common';
import localeEs from '@angular/common/locales/es';
import localeEsExtra from '@angular/common/locales/extra/es';
registerLocaleData(localeEs, 'es-ES', localeEsExtra);
.
.
.
  providers: [
    { provide: LOCALE_ID, useValue: 'es' }
  ],
-----------------------------------------------------------------
-----------------------------------------------------------------
index.html
-----------------------------------------------------------------
.
.
.
<html lang="es">
.
.
.
-----------------------------------------------------------------
-----------------------------------------------------------------
#npm install bootstrap --save-dev
** warning una vulneravilidad por lo cual => npm-upgrade
#npm install jquery --save-dev
#npm install popper.js --save
#npm install tether --save
-----------------------------------------------------------------
configuré typescript en 3.2.4 en package.json porque no me andaba
