Forked from Angular2 Quickstart project here: https://github.com/angular/quickstart

Applied ngc and rollup to the main application bundle (app code and angular library) per instructions here: https://angular.io/docs/ts/latest/cookbook/aot-compiler.html#!#source-code

Polyfills - core-js, zone-js and reflect-metadata - were left un-optimized.

Issues:

Still cannot use templateUrl and moduleId in @Component. Error related to moduleId occurs! Workaround - remove moduleId and use inline template.