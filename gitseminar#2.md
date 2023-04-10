# Создание туториала по Git
## Как создать репозиторий
**Чтобы создать репозиторий, напишите следующую команду в терминал:**
```fix 
git init
```

## Как добавить файл на отслеживание
**Чтобы добавить файл на отслеживание, вам будет необходимо сделать следующее:**
- прописать команду git add.


# Руководство по MarkDown

## Раздел первый - заголовки




## Раздел второй - Списки

Для разметки неупорядоченных списков можно использовать или `*`, или `-`, или `+`:

- элемент 1
- элемент 2
- элемент ...

Вложенные пункты создаются четырьмя пробелами перед маркером пункта:

* элемент 1
* элемент 2
 * вложенный элемент 2.1
 * вложенный элемент 2.2
* элемент ...

Упорядоченный список:

1. элемент 1
2. элемент 2
     1. вложенный
     2. вложенный
3. элемент 3
4. Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse id sem onsectetuer libero luctus adipiscing.

На самом деле не важно как в коде пронумерованы пункты,
главное, чтобы перед элементом списка стояла цифра
(любая) с точкой. Можно сделать и так:

0. элемент 1
0. элемент 2
0. элемент 3
0. элемент 4

Список с абзацами:

* Раз абзац. Lorem ipsum dolor sit amet, consectetur adipisicing elit.
* Два абзац. Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse id sem consectetuer libero luctus adipiscing.
* Три абзац. Ea, quis, alias nobis porro quos laborum minus sed fuga odio dolore natus quas cum enim necessitatibus magni provident non saepe sequi?

    Четыре абзац (Четыре пробела в начале или один tab).



## Раздел третий - исходный код





## Раздел четвертый - таблицы

**В чистом Маркдауне нет синтаксиса для таблиц, а в GFM есть.**
First Header | Second Header
------------ | -------------
Content Cell | Content Cell
Content Cell | Content Cell

**Для красоты можно и по бокам линии нарисовать:**

| First Header | Second Header |
| -------------| ------------- |
| Content Cell | Content Cell  |
| Content Cell | Content Cell  |

**Можно управлять выравниванием столбцов при помощи двоеточия.**

| Left-Aligned | Center Aligned | Right Aligned |
|:------------ |:--------------:| -------------:|
| col 3 is     | some wordy text | **$1600** |
| col 2 is | centered | $12 |
| zebra stripes | are neat | ~~$1~~ |

**Внутри таблиц можно использовать ссылки, наклонный, жирный или зачеркнутый текст. Для всего остального есть обычный HTML.**

