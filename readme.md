# gulp-concat-dir2

## install
```sh
npm install gulp-concat-dir2 --save-dev
```

## example
```js
var gulp = require('gulp');
var concat = require('gulp-concat-dir2');

gulp.task('concat', function(){
	return gulp
		.src('src/js/**/*.js')
		.pipe(concat({ext:'.js'}))
		.pipe(gulp.dest('dest/js'));
});
```