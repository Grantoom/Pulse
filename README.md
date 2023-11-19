# Проект "Пульс"

## Описание проекта

Проект "Пульс" представляет собой веб-приложение, разработанное с использованием методологии БЭМ (Блок, Элемент, Модификатор), автоматизации сборки с помощью Gulp, и структурированного стиля оформления с использованием препроцессора SCSS и языка программирования JavaScript. В проекте реализована отправка данных для обратной связи с покупателем, с помощью PHPMailer.

## Технологии

### 1. БЭМ (Блок, Элемент, Модификатор)

Мы используем методологию БЭМ для построения структуры проекта и управления CSS-классами. Это позволяет нам создавать компонентный и легко поддерживаемый код.

### 2. Gulp

Автоматизация сборки проекта осуществляется с использованием Gulp - популярного инструмента для автоматизации задач. Gulp управляет процессами, такими как компиляция SCSS в CSS, минификация и объединение файлов, а также другие задачи, упрощая процесс разработки.

### 3. SCSS

Препроцессор SCSS (Sassy CSS) используется для написания более поддерживаемого и структурированного кода стилей. SCSS предоставляет множество возможностей, таких как переменные, миксины и вложенность, улучшая читаемость и поддерживаемость кода стилей.

### 4. JavaScript

JavaScript используется для создания интерактивных элементов на странице. Мы следуем современным практикам разработки, обеспечивая производительность и чистоту кода.

## Установка

Для запуска данного проекта, вам необходимо иметь установленные Node.js и NPM. После клонирования репозитория, выполните следующие команды:

1. Установите Node.js и NPM, если их еще нет на вашем компьютере.
2. Установите все зависимости проекта, запустив следующую команду в корневом каталоге проекта:

```bash
npm install
```
## Запуск проекта
Чтобы собрать проект и запустить его локальный сервер разработки, выполните следующую команду:

```bash
gulp
```
Вам также нужно будет убедиться, что у вас на машине глобально установлен Gulp. Если его нет, вы можете установить его, запустив следующую команду:

```bash
npm install --global gulp-cli
```
