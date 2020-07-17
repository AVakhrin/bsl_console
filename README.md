# Консоль кода для 1С 8.3 (Управляемые и обычные формы)

Для работы внутри 1С требуется версия платформы не ниже **8.3.14.1565** 

![](https://github.com/salexdv/git_images/blob/master/bslconsole_view.png?raw=true)

## Как работает?
На основе [Monaco editor](https://github.com/Microsoft/monaco-editor)

## Основные возможности:
* Подсветка синтаксиса языка 1С
* Автокомплит для глобальных перечислений и функций
* Автокомплит для метаданных (Справочники, Документы и т.п.)
* Автокомплит для объектов метаданных (СправочникСсылка, ДокументОбъект и т.п.)
* Подсказка параметров конструкторов и методов
* Вставка готовых блоков кода (сниппеты)

## Перед запуском
По умолчанию основные браузеры блокируют загрузку файлов с локальной машины, а все описания синтаксиса лежат тут же в JSON, поэтому тот же Chrome надо запускать с ключом *--allow-file-access-from-files*

## Благодарности
Выражаю благодарность команде [1c-syntax](https://github.com/1c-syntax) и их [проекту для VSCode](https://github.com/1c-syntax/vsc-language-1c-bsl) за подробное описание внутренних конструкций языка в JSON
