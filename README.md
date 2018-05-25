# Курс вёрстки лендинга itvdn

## Перед стартом проекта необходимо:

* Убедиться, что установлены nodejs и npm. Для этого выполнить в терминале команды:

> node -v

Если вы видите номер версии, то всё ОК
Если нет, то заходим на https://nodejs.org/en/ и ставим версию LTS

> npm -v
Также должна отобразиться версия (npm идёт в составе nodejs)

* Убедиться, что установлен gulp 4 версии. Если нет, то ставим:

> npm install gulpjs/gulp-cli -g

> npm install gulpjs/gulp --save-dev

> gulp -v

Должен показать что-то вроде:
[21:49:27] CLI version 2.0.1
[21:49:27] Local version 4.0.0

## Инструкции для старта проекта:
* Склонировать репозиторий
> git clone https://github.com/sergeyamator/itvdn-landing.git

* Запустить команду npm install в терминале, которая установит все пакеты, указанные в файле package.json, а также все их зависимости

* Файл package.json содержит секцию Scripts,
куда можно дописывать свои команды. Например, в нашем случае напишем команду Start, которая будет просто запускать gulp с его задачей по умолчанию:
"start": "gulp"
Для выполнения команды Start в окне терминала надо набрать:
> npm start

## Домашнее задание
1. Git - знать команды:
- git status
- git add
- git commit -m "some comment"
- git push
- git branch
- git checkout
- git merge

2. Gulp 
- попрактиковаться с установкой галпа и его пакетов
- autoprefixer и sourcemaps => Разобратьсся что это и установить в проект



## Урок 4.
Доустановить стили и нормалайз:
> npm install --save font-awesome normalize.scss








