# dropdown

## Назначение

Блок представляет собой элемент интерфейса, скрывающий своё содержимое и отображающий его по щелчку по метке.

Служит основой для нескольких других элементов.

## Структура

Структура результирующего элемента:

    .dropdown
      input.dropdown__show
      label.dropdown__backdrop
      label.dropdown__label
      .dropdown__content
        block

## Использование

### Применение шаблона
    +dropdown(
        text,
        dropdownAttr,
        cbAttr,
        backdropAttr,
        labelAttr,
        contentAttr) content

### Аргументы шаблона

Шаблон принимает аркументами:

1. Текст, отображаемый на всегда отображаемой метке.
2. Атрибуты охватывающего элемента.
3. Атрибуты чекбокса, служащего для открытия/закрытия дропдауна.
4. Атрибуты элемента, занимающего при открытом дропдауне весь экран и служащего для отлова щелчков мышью за пределами элемента.
5. Атрибуты всегда отображаемой метки.
6. Атрибуты блока с содержимым.

### Значения

Отсутствуют

## Зависимости

Данный элемент не зависит от других.