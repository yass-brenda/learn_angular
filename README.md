
# Angular

Es un Framework para crear aplicaciones web __SPA(Single Page Application)__.
Desarrollado por __Google__.

__Características__
- Separa el Frontend del Backend.
- Simplifica el código.
- Sigue el patrón MVC.
- Basado en Componentes.
- Es de código abierto.

Utiliza el lenguage __Typescript__ derivación de Javascript.

__Ventajas__

- El desarollo de aplicaciones es rápido
  - La navegación para ellas también.
- Es modular
  - Reutilizable.
- Fácil mantenimiento
- Es multiplataforma.
- Futuro estable .
- Soporte para trabajar en diferentes herramientas.

__ Abrir el servidor en tu navegador __

1- Colocate dentro del proyecto que ejecutaras.
2- Coloca el siguiente comando en consola __ng serve -o__
3. Verás que se abrio la aplicación en tu navegador.
4. Cuando tu cursor este parpareando quiere decir que tu servicio esta funcionando.
5. Para detener tu servidor usa CTRL + C .


Cuando se desplega la aplicación solo se sube la carpeta _src__.
Todos los demás archivos son para que puedas trabajar en local, durante el desarrollo.

# Archivo Index.html
En el body se llama el primer componente de la siguiente manera.
```
<body>
  <app-root></app-root>
</body>
```

Si usas windows y te sale un error deber irte al powerShell y ejecutar lo siguiente:
Set-ExecutionPolicy Unrestricted

# PildorasAngular

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.2.1.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
