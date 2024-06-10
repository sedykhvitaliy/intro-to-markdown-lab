# The Anatomy of a CSS Selector
![img](https://images.unsplash.com/photo-1523437113738-bbd3cc89fb19?q=80&w=2671&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

CSS (Cascading Style Sheets) selectors are fundamental building blocks for styling web pages.

## 1. Selector
A CSS selector targets HTML elements to apply styles. It can be a tag name, class, ID, attribute, or a combination of these.

***Example:***

```CSS
/* Tag name selector */
p {
    color: blue;
}

/* Class selector */
.myClass {
    font-size: 16px;
}

/* ID selector */
#myID {
    background-color: lightgray;
}
```

## 2. Universal Selector
Selects all elements on a page.

***Example:***

```CSS
* {
    margin: 0;
    padding: 0;
}
```
## 3. Descendant Selector
Selects elements that are descendants of another element.

***Example:***

```CSS
div p {
    font-style: italic;
}
```

For more information about CSS, check out the MDN docs. 
[MDN](https://developer.mozilla.org/en-US/docs/Learn/CSS)