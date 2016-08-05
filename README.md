# gulp

在根目录下，窗个文件，需配合命令进行，压缩啊、合并、重命名啊

列如：npm install gulp
  
      npm install gulp-uglify
      
      
      
      
      
      var gulp = require('gulp'),
	uglify=require('gulp-uglify');
	gulp.task('mygulp',function(){
		gulp.src('jquery-1.12.0.js')
		.pipe(uglify())
		.pipe(gulp.dest("he"))
	})
      


