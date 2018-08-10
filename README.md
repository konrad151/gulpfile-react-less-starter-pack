# gulpfile-react-less-starter-pack

This starter pack include browserSync configured for JS and LESS files.

### JS:
- React rendering
- compile ES6 (babelify)
- modules support (browserify)
- minify JavaScript (uglify)
### LESS:
- concat
- compile to CSS
- minify CSS

### Installation
Install the dependencies
```
$ npm install
```
### Run gulp
Run Gulp tasks with browserSync,<br />
gulp will be watching your JS files from app/src/js/*.js and LESS files from app/src/less/*.less,<br />
every saved change will be compiled into app/dist directory
```
$ gulp
```