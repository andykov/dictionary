# Словарь терминов CSS

Оглавление: [A](#a) [B](#b) [C](#c) [D](#d) [E](#e) [F](#f) [G](#g) [H](#h) [I](#i) J [K](#k) [L](#l) [M](#m) [N](#n) [O](#o) [P](#p) [Q](#q) [R](#r) [S](#s) [T](#t) [U](#u) [V](#v) [W](#w) X Y Z

### at-keyword

**ключ директивы,** см. [директива](#at-rule)

### at-rule

**директива,** тип [объявления](#statement), начинающегося со знака `@`, напр. _@import_.

### block

1. **блок деклараций,** структурная часть [объявления](#statement). Заключается в фигурные скобки и содержит декларации свойств (или, в случае медиавыражения, блоки стилей).
2. **блочный вид,** см. [вид](#display)

### comment

**комментарий,** пояснение к коду

### color

**цвет**

### combinator

**комбинатор,** специальный символ, использующийся в сложном селекторе для точного указания комбинации DOM-элементов, напр. `>`, `+` и др. Пробел между селекторами также считается комбинатором.

- descendant combinator — **комбинатор потомка,** ` ` (пробел).
- child combinator — **комбинатор непосредственного потомка,** `>`. Также называется **дочерним**.
- adjacent sibling combinator — **комбинатор непосредственного соседства,** `+`.
- general sibling combinator — **комбинатор соседства,** `~`.

### declaration

**декларация,** объявление свойства и значения.

### function

**функция**

1. в программировании — поименованный фрагмент программного кода (подпрограмма), к которому можно обратиться из другого места программы.
2. в CSS — может быть присутствовать в [декларации](#declaration) на позиции значения. Напр., `url(img/gradient.png)`.

### keyword

**ключевое слово**

### length

**длина**

### media query

**медиавыраже́ние,** объявление директивы `@media` с некими [условиями](#media-query-list), позволяет применять стили в зависимости от возможностей устройства. Вариант перевода «медиазапросы» менее точно отражает суть работы.

### media query list

**условия медиавыражения,** список условий, определяющих, в каких случаях будут применяться объявления внутри директивы `@media`. Напр., `only screen and (min-width: 35em)`.

### media type

**тип устройства,** может быть условием медиавыражения. Определяет тип устройства. Напр., `screen`.

### media feature

**характеристика устройства,** может быть условием медиавыражения. Определяет характеристику устройства. Напр., `min-width`.

### number

**число, числовой тип**

### percentage

**процентное значение, проценты**

### property

**свойство,** напр. _CSS-свойство_.

### pseudo-element

**псевдоэлемент,** дополнительный внутренний элемент, созданный с помощью CSS и `::before` или `::after`.

### pseudo-class

**псевдокласс,** используется для привязки декларации к определенному состоянию элемента DOM. Отделяется от селектора знаком двоеточия `:`. Напр., декларация блока правил с селектором `.item:hover` применится, когда на `.item` наведут курсор.

### rule-set

**блок стилей элемента**, состоит из селектора (или медиавыражения) и блока деклараций.

### selector

**селектор,** необходимая структурная часть [блока стилей](#rule-set). Отвечает за привязку деклараций к элементам DOM.

- simple selector — **простой селектор,** может быть [псевдоклассом](#pseudo-class) или одним из следующих типов:
    - type selector — **селектор по типу,** обращается к тегу, напр. `ul`, `input` и др.
    - universal selector — **универсальный селектор,** «звездочка»: `*`.
    - ID selector — **селектор по идентификатору,** напр. `#content`.
    - class selector — **селектор по классу,** напр. `.item`.
    - attribute selector — **селектор по атрибуту,** напр. `[type=submit]`.
- compound selector (др. sequence of simple selectors) — **составной селектор**, цепочка простых селекторов, не разделенных комбинаторами, напр. `input[type=submit]:focus`.
- complex selector — **сложный селектор**, несколько простых и/или составных селекторов, разделенных комбинаторами:
    - descendant selector — **селектор потомка**, напр. `ul li`.
    - child selector — **селектор непосредственного потомка**, напр. `#buttons > *`. Также часто называется **дочерним**.
    - adjacent sibling selector — **селектор непосредственного соседства**, напр. `.item + .item`. Также часто называется **соседским**.
    - general sibling selector — **селектор соседства**, напр. `.item ~ .item`.


### statement

**объявление**, структурный элемент CSS. Это может быть блок стилей элемента, директива импорта, медиавыражение и т.д.

### string

1. **строковый тип,** в программировании — тип данных, значениями которого является произвольная последовательность (строка) символов алфавита.
2. **строка,** в CSS — строковое значение директивы или свойства. Напр., в `content: "\201d"` строкой является `"\201d"`.

### unit

**единица изменения,** напр. _rem unit — единица измерения «рем»._

### URL

1. _разг._ **адрес**. Значение рекомендовано к использованию при переводах статей.

2. **унифицированный указатель ресурса,** [URI](#URI), который предоставляет ещё и информацию о местонахождении этого ресурса, напр. _background: url("http://www.example.com/picture.png")_

### value

**значение,** напр. _значение CSS-свойства_.

### vendor prefix

**бра́узерный пре́фикс,** приставка к CSS-свойству `-webkit-` или `-moz-`, напр. _add vendor prefixes — добавьте браузерные префиксы._

---
[Авторы](https://github.com/web-standards-ru/dictionary/graphs/contributors), редактор [Вадим Макеев](http://pepelsbey.net). Распространяется по лицензии [CC-BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/).
