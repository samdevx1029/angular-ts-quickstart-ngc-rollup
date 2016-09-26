Forked from Angular2 Quickstart project here: https://github.com/angular/quickstart

Applied ngc and rollup to the main application bundle (app code and angular library) per instructions here: https://angular.io/docs/ts/latest/cookbook/aot-compiler.html#!#source-code

Polyfills - core-js, zone-js and reflect-metadata - were left un-optimized.

Removed files related to tests and docker.

Issues:

Still cannot use templateUrl and moduleId in @Component. Error related to moduleId occurs! My workaround - remove moduleId and use inline template.

Instructions:

Download and run "npm install".

To build with ngc and rollup, "npm run build", followed by "npm run serve" to serve the built app.

To run with live reload, "npm run start" which builds first with "npm run build", then live-reloads with concurrently.