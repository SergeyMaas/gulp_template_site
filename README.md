# Шаблон окружения front-end с Gulp и плюшками
Готовое окружение для разработки front-end части сайта

### Состав окружения
```javascript
var gulp        = require('gulp'),
    watch       = require('gulp-watch'),
    prefixer    = require('gulp-autoprefixer'),
    uglify      = require('gulp-uglify'),
    sass        = require('gulp-sass'),
    sourcemaps  = require('gulp-sourcemaps'),
    rigger      = require('gulp-rigger'),
    cssmin      = require('gulp-minify'),
    imagemin    = require('gulp-imagemin'),
    pngquant    = require('imagemin-pngquant'),
    rimraf      = require('rimraf'),
    browserSync = require('browser-sync');
```
### Команды
1. `gulp html:build`.
2. `gulp style:build`.
3. `gulp js:build`.
4. `gulp image:build`.
5. `gulp fonts:build`.

### Использование
1. Клонируем и заходим в папку проекта.
2. Выполняем в консоли `npm i` или `sudo npm i`.
3. Выполняем в консоли `bower i` или `sudo bower i`.
4. Выполняем в консоли `gulp`.