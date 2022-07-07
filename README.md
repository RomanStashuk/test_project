# Project-start-template (Gulp)
Стартовий шаблон для проекту на основі таск-менеджера Gulp
___
## Як користуватись
`npm install` – встановлення пакетів та залежностей<br><br>
`npm test` – запуск перевірки наявності стилістичних помилок<br><br>
`npm start` – збирання проекту в режимі розробки із запуском локального сервера<br><br>
`npm run build` – фінальне збирання проекту <br><br>
`npm run deploy` – фінальне збирання проекту із деплоєм його в [GitHub Pages](https://pages.github.com)<br><br>
`npm run dist` – фінальне збирання проекту із архівацією його в форматі zip<br>
___
## Файлова структура
```bash
├── build/                      # каталог збірки проекту (створюється автоматично)
├── dist/                       # каталог з zip архівом зібраного проекту (створюється автоматично)
├── gulpfile.js/                # каталог з файламим для Gulp
│   ├── config/                 #
│   │   ├── app.js              #
│   │   └── pats.js             #
│   ├── data/                   #
│   ├── tasks/                  #
│   └── index.js                #
├── src/                        # каталог для размещения исходных файлов проекта
│   ├── css/                    # каталог CSS файлів стилів 
│   │   ├── base/               #
│   │   │   └── global.css      #
│   │   ├── blocks/             #
│   │   └── style.css           #
│   ├── fonts/                  # каталог шрифтів
│   ├── html/                   #
│   │   ├── blocks/             #
│   │   └── index.html          #
│   ├── img/                    # каталог зображень
│   │   └── icons/              # каталог векторних зображень для генерації спрайта
│   ├── js/                     # каталог JS файлів
│   │   ├── modules/            #
│   │   └── main.js             #
│   ├── pug/                    #
│   │   ├── blocks/             #
│   │   ├── layout/             #
│   │   │   └── app.pug         #
│   │   └── index.html          #
│   └── sass/                   # каталог SASS/SCSS файлів стилів
│   │   ├── base/               #
│   │   │   ├── global.scss     #
│   │   │   ├── mixins.scss     #
│   │   │   └── variables.scss  #
│   │   ├── blocks/             #
│   │   └── style.scss          #
├── .babelrc                    # файл конфігурації Babel
├── .editorconfig               # файл з налаштуваннями редактора
├── .eslintrc.json              # файл конфігурації ESLint
├── .npmrc                      # файл конфігурації npm
├── .stylelintrc.json           # файл конфігурації stylelint
├── .gitattributes              # файл атрибутів Git
├── .gitignore                  # файл для виключень Git
├── README.md                   # документація проекту
├── package-lock.json           # lock-файл npm
└── package.json                # файл npm залежностей та налаштувань
```
