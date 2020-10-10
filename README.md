* 0.0 Скачать исходники сборки:
* 0.1 git clone https://github.com/sellsteam/www.git -> yarn
----------------------------------------------------------------------------------------------------
* 1.0 Если до этого не использовали сборку выполните след инструкции:
* 1.1 Установите node.js и yarn
* 1.2 Установите gulp ```yarn global add gulp-cli``` (в консоль)
* 1.3 Установите БЭМ-инструменты: ```yarn global add bem-tools-core```
----------------------------------------------------------------------------------------------------
* 2.0 После манипуляций выше перейти в папку проекта и прокинуть в консоль след команды:
* 2.1 ``` yarn ``` - скачать все зависимости
* 2.1 Затем можно переходить к пункту - 3.0
----------------------------------------------------------------------------------------------------
* 3.0 Команды для работы:
* ```yarn run dev``` - запуск сервера для разработки проекта
* ```yarn run build``` - собрать проект с оптимизацией без запуска сервера
----------------------------------------------------------------------------------------------------
* Файловая структура проекта:
```
starter
├── dist
├── gulp-tasks
├── src
│   ├── blocks
│   ├── fonts
│   ├── img
│   ├── js
│   ├── styles
│   ├── views
│   └── .htaccess
├── gulpfile.babel.js
├── webpack.config.js
├── package.json
├── .babelrc.js
├── .bemrc.js
├── .eslintrc.json
├── .stylelintrc
├── .stylelintignore
└── .gitignore
```
