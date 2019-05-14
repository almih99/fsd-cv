# rate-button

## Назначение

Блок представляет собой обёртку над группой html элементом `<input type="radio">`, служащую для кастомизации внешнего вида.

## Структура

Структура результирующего элемента:

    .rate-button
      input.rate-button__input(value=1)
      label.rate-button__label
      ...
      input.rate-button__input(value=5)
      label.rate-button__label


## Использование

### Применение шаблона
    +checkbox(
        name, 
        value, 
        rateAttributes)

### Аргументы шаблона

Шаблон принимает аркументами:

1. Имя, для предоставления значения форме.
2. Номер изначально выбранного значения.
3. Атрибуты охватывающего элемента.

### Значения

Предоставляются стандартным html элементом `<input type="radio">`

## Зависимости

Данный элемент не зависит от других.