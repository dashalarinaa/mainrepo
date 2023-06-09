# Туториал по основам системы контроля версий GIT


## Инициализация проекта
**Чтобы добавить возможность использовать разные версии файлов, необходимо использовать следующую команду:**

```fix
git init
```


## Как добавить файл в отслеживание
**Чтобы добавить файл на отслеживание, используйте следующую команду:**

```
git add .
```

## Узнать состояние файлов
**Чтобы узнать, какие файлы изменены, но не добавлены в индекс; какие ожидают коммита в индексе, введите следующую команду:**

###### git status

## Чтобы вычислить разницу между версиями, используйте команду:
-git diff

## Существует много команд:
1. git log
2. git reflog

# Инструкция - туториал по разметке MarkDown


## Заголовки

Заголовки отмечаются диезом `#` в начале строки, от
одного до шести. Например:
# Заголовок первого уровня #
## Заголовок h2
### Заголовок h3
#### Заголовок h4
##### Заголовок h5
###### Заголовок h6


## Исходный код

В чистом Маркдауне блоки кода отбиваются 4 пробелами в начале
каждой строки.
Но в GitHub-Flavored Markdown (сокращенно GFM) есть более
удобный способ: ставим по три апострофа (на букве Ё) до и после
кода. Также можно указать язык исходного кода.


## Таблицы

В чистом Маркдауне нет синтаксиса для таблиц, а в GFM
есть.
First Header | Second Header
------------- | -------------
Content Cell | Content Cell
Content Cell | Content Cell
Для красоты можно и по бокам линии нарисовать:
| First Header | Second Header |
| ------------- | ------------- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |
Можно управлять выравниванием столбцов при помощи
двоеточия.
| Left-Aligned | Center Aligned | Right Aligned |
|:------------- |:---------------:| -------------:|
| col 3 is | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |
Внутри таблиц можно использовать ссылки, наклонный,
жирный или зачеркнутый текст.
Для всего остального есть обычный HTML.




## Изображения

** Чтобы добавить изображения, воспользуйтесь следующей командой:**

```
![Альтернативный текст](ссылка на это фото)
```
Пример:
![Здесь был Вася и его фото](https://images.unsplash.com/photo-1517649763962-0c623066013b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1170&q=80)

**Если свое фото, то указываем название:**

![мое фото](DSC_3794.jpg)

**Если мы хотим добавить изображения-ссылки, то нашу конструкцию можно сделать такой:**

```
[![альтернативный текст(ссылка)]](Ссылка на другую картинку - наш перевертыш)
```
[![Фото Васи и Пети - нажми, получишь бонус](https://images.unsplash.com/photo-1517649763962-0c623066013b?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1170&q=80)](https://media.istockphoto.com/id/1464605292/ru/%D1%84%D0%BE%D1%82%D0%BE/%D1%81%D1%82%D0%B0%D1%80%D1%88%D0%B8%D0%B9-%D1%87%D0%B5%D1%80%D0%BD%D0%B0%D1%8F-%D0%BF%D0%B0%D1%80%D0%B0-%D1%85%D0%BE%D0%B4%D1%8C%D0%B1%D0%B0-%D0%BE%D1%82-%D1%82%D0%B5%D0%BD%D0%BD%D0%B8%D1%81%D0%BD%D0%BE%D0%B3%D0%BE-%D0%BA%D0%BE%D1%80%D1%82%D0%B0.jpg?s=612x612&w=is&k=20&c=rVYixmaCs1vHtjejQoITvaGFmOdKBkn14rSlE731nJY=)

тест
