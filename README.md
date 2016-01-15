gulp-middleman
==============

Gulp plugin for running Middleman

# Usage example

```
var middleman = require('gulp-middleman');

// Local Dev
gulp.task('middleman', function() {
  middleman.server({ 
    server: 'localhost',
    useBundler: true
  })
});

// Build
gulp.task('middleman:build', function() {
  middleman.build()
});
```
