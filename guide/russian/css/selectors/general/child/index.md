---
title: Child
localeTitle: ребенок
---
## ребенок

Селектор child представлен символом `>` и помещается между двумя селекторами: `parent > child` . Он соответствует любому второму селектору, который является потомками первого селектора (родителя). Второй селектор должен быть непосредственным потомком первого.

Вот пример синтаксиса:

```css
first selector (parent) > second selector (child) { 
    css declarations; 
 } 
```

Вот пример кода, который соответствует всему непосредственному элементу `span` с родителем `div` :

```css
div > span { 
    background-color: red; 
 } 
```

### Дополнительная информация:

*   [Детский селектор W3C Рабочий проект](https://www.w3.org/TR/CSS22/selector.html#child-selectors)