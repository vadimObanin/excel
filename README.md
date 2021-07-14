# Excel на чистом JS

Ссылка на рабочий проект в интернете - http://mortido.bget.ru/

`npm run start` - start project

`npm run build` - build project

## Описание проекта

Целью данного проекта было создание рабочей версии аналога google spreadsheet на чистом JS (с тестовым функционалом). 

## Основные возможности

- создание таблиц (последующее редакитирование и удаление) с сохранением в local storage
- роутинг между страницами и панелью управления
- работа со строкой формулы (fx). После добавления знака равно в строке fx можно реализовать основные арифметические операции (в ячейке будет отображен результат арифметических операций)
- форматирование текста в ячейках (выравнивание, выделение)
- ресайз ячеек таблицы
- переименование таблиц
- возможность создания нескольких независимых таблиц

## Проделанная работа

- настройка webpack
- работа с eslint
- работа с git (git flow)
- верстка таблицы
- создание фреймворка для работы с компонентами и DOM
- добавление прослушки событий
- ресайз таблицы (его последующая оптимизация по обноалению DOM)
- функционал по выделению группы ячеек через shift
- взаимодействие между компонентами
- синхронизация содержимого ячеек и компонента формулы (fx)
- роутинг
- сохраниние данных таблиц в local storage
- сохранение таблиц и навигация между ними
- удаление страниц
- фунционал по реализации арифметических операций через строку - компоненту формулы (fx)
- создание панели управления таблицами с возможностью открытия ранее созданных таблиц
