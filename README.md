# Mesh Angular Demo

This is a simple example application intended to demonstrate a few of the features of Gentics Mesh 
([getmesh.io](http://getmesh.io)).

All calls to the Mesh API endpoints are made from the [`MeshService`](app/mesh.service.ts). The rest of the 
app logic is contained in the [app component](app/app.component.ts) file.

The app is using Angular and built with [Angular CLI](https://github.com/angular/angular-cli). Run `ng serve`
to start a dev server at `http://localhost:4200/`, `ng build --dist` to build the project to `dist/`.

This is intended to be an extremely simple example. Therefore the implementations
are necessarily naive. The idea is to provide a way to see the Mesh API in action and provide an example for
interested developers to experiment with.
