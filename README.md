#Frontend Skeleton

Skeleton app for building frontend apps.

Incudes [karma](https://karma-runner.github.io/0.13/index.html), [browserify](http://browserify.org/), [watchify](https://github.com/substack/watchify), [lessify](https://www.npmjs.com/package/lessify) and [gulp](http://gulpjs.com/).

## Installing

### Setup

`npm run setup` will install [gulp](http://gulpjs.com) and install all dependencies.
 
 `npm start` spins up a dummy page loaded with `dist.js`.

## Building

Navigate to the `build` directory and run `gulp` to run karma tests and build.

Output file, `dist.js`, will be under the `dist` directory.

## Gulp commands

- `gulp`: runs tests and builds

- `gulp build`: builds

- `gulp server`: starts a test server that loads up a dummy page, which loads the built script `dist.js` (under `dist` dir)

- `gulp test`: runs tests

- `gulp test -w`: runs tests and watches for any changes to re-run tests (**no rebuild**)

- `gulp watch`: spins up a test server, builds and watches for any changes; if changes, runs tests, rebuilds and reloads webpage. this is what `npm start` runs
