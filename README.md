# Верстка лендинга 

## Перед стартом проекта необходимо

> node -v 

Если вы видите версию, например, vx.x.x. тогда все ок
Если ошибка то необходимо установить node.js

> npm -v

https://www.npmjs.com - репозиторий всех пакетов 
Если вы видите версию, например, x.x.x тогда все ок

* Убедиться что установлен gulp 4 версии, так как если будет меньше - работать не будет. 
Если он не установлен - тогда ставим:

# Uninstall previous Gulp installation and related packages, if any
$ npm rm gulp -g
$ npm rm gulp-cli -g
$ cd [your-project-dir/]
$ npm rm gulp --save-dev
$ npm rm gulp --save
$ npm rm gulp --save-optional
$ npm cache clean

# Install the latest Gulp CLI tools globally
$ npm install gulpjs/gulp-cli -g

# Install Gulp 4 into your project from 4.0 GitHub branch as dev dependency
$ npm install gulpjs/gulp#4.0 --save-dev

# Check the versions installed. Make sure your versions are not lower than shown.
$ gulp -v
---
[10:48:35] CLI version 1.2.2
[10:48:35] Local version 4.0.0-alpha.2

## Инструкция для старта проекта 

* Склонировать данный репозиторий
>  git clone https://github.com/AleksandrZh/land.git

Запустить команду npm install в терминале. Данная команда установит все пакеты, которые указанны в файле 
	packege.json, а также все их зависимости
----------------------------------------------------------------------------еесли создаается с нуля  	
    git status - посмотреть  какие файлы с изменениями 
	
	git add README.md .gitignore package.json 
	
	дальше необходимо сделать commit(снимок)
	
	git commit -m "First initialization" 

Все хранится локально, теперь что - бы отправить все на удаленный репозиторий необходимо:



git remote add origin https://github.com/AleksandrZh/land.git
git push -u origin master

Для того что бы создать файл package.json необходимо либо создать его в ручную, либо запустить комманду 

npm init
-------------------------------------
## Установка пакетов

browsersync

https://www.browsersync.io/

https://www.browsersync.io/docs/gulp

npm install browser-sync gulp-pug jquery gulp-sass --save-dev

npm i gulp.spritesmith --save-dev

npm install rimraf --save-dev

npm install gulp-rename --save-dev



	
	
