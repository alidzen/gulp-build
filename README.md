## Gul-build: сборка для быстрого развертывания проекта.

### Состав.
#### Gulp-плагины:
&mdash; [gulp-autoprefixer](https://www.npmjs.com/package/gulp-autoprefixer)  
&mdash; [gulp-minify-css](https://www.npmjs.com/package/gulp-minify-css)  
&mdash; [browser-sync](https://www.npmjs.com/package/browser-sync)  
&mdash; [gulp-imagemin](https://www.npmjs.com/package/gulp-imagemin)  
&mdash; [imagemin-pngquant](https://www.npmjs.com/package/imagemin-pngquant)  
&mdash; [gulp-uglify](https://www.npmjs.com/package/gulp-uglify)  
&mdash; [gulp-sass](https://www.npmjs.com/package/gulp-sass)  
&mdash; [gulp-surcemaps](https://www.npmjs.com/package/gulp-sourcemaps)  
&mdash; [gulp-rigger](https://www.npmjs.com/package/gulp-rigger)  
&mdash; [gulp-watch](https://www.npmjs.com/package/gulp-watch)  
&mdash; [rimraf](https://www.npmjs.com/package/rimraf)  

##### Прочее:  
&mdash; [normalize.css](https://github.com/necolas/normalize.css)

### Установка.
1. Клонируем репозиторий:  
>git clone https://github.com/alidzen/gulp-build.git

2. Устанавливаем все компоненты:  
>npm install --save-dev gulp-autoprefixer --save-dev gulp-minify-css browser-sync gulp --save-dev --save-dev gulp-imagemin --save imagemin-pngquant --save-dev gulp-uglify gulp-sass --save-dev gulp-sourcemaps --save-dev gulp-rigger gulp-watch rimraf  

>bower i

3. Запускаем Gulp:  

>gulp

### Структура:  
* src-папка &mdash; рабочая дерриктория проекта, т.е. все входящие документы храняться и подключаются здесь.   
* build-папка &mdash; готовые файлы, сжатые картинки, стили и т.д..

### P.s.:   
Для того, чтобы шрифты и изображения правильно работали, необходимо в папке src создать рабочие папки с именами: fonts и img, соответственно.  

Для работы сборки необходимы: 

&mdash; [Node JS](http://nodejs.org/) версия 3.8.11 и выше.  
&mdash; [Bower](http://bower.io/)  
&mdash; [Gulp Js](http://gulpjs.com/)  



