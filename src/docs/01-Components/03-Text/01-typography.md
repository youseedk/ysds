<nav class="element-navigation">
  <dl class="element-navigation__list">
    <dt class="element-navigation__title">Table of contents</dt>
    <dd class="element-navigation__item">[Examples](#examples)</dd>
    <dd class="element-navigation__item">[HTML Guidelines](#html-guidelines)</dd>
    <dd class="element-navigation__item">[UX and Design Guidelines](#ux-and-design-guidelines)</dd>
  </dl>
</nav>

# Examples
## Main title
<div class="element-preview">
  <div class="element-preview__inner">{{render '@typography--default'}}</div>
</div>

```html
{{render '@typography--default'}}
```

## Primary title
<div class="element-preview">
  <div class="element-preview__inner">{{render '@typography--primary-title'}}</div>
</div>

```html
{{render '@typography--primary-title'}}
```

## Secondary title
<div class="element-preview">
  <div class="element-preview__inner">{{render '@typography--secondary-title'}}</div>
</div>

```html
{{render '@typography--secondary-title'}}
```

## Subtitle
<div class="element-preview">
  <div class="element-preview__inner">{{render '@typography--subtitle'}}</div>
</div>

```html
{{render '@typography--subtitle'}}
```

## Body text
<div class="element-preview">
  <div class="element-preview__inner">{{render '@typography--body-text'}}</div>
</div>

```html
{{render '@typography--body-text'}}
```

## Legal text
<div class="element-preview">
  <div class="element-preview__inner">{{render '@typography--legal-text'}}</div>
</div>

```html
{{render '@typography--legal-text'}}
```

## Unordered list
<div class="element-preview">
  <div class="element-preview__inner">{{render '@typography--unordered-list'}}</div>
</div>

```html
{{render '@typography--unordered-list'}}
```

## Ordered list
<div class="element-preview">
  <div class="element-preview__inner">{{render '@typography--ordered-list'}}</div>
</div>

```html
{{render '@typography--ordered-list'}}
```

# HTML Guidelines
Always mark up text semantically, ie. only use one `<h1>` per page, even if the design shows two “Main Title” elements. The visual representation is handled by CSS and not the HTML.

Please be aware that the color of the text is not set in the CSS classes and should be set on the parent element.

# UX and Design Guidelines
For accessibility reasons we should aim for a line-height adhering to the 8 point grid, which means rounding up numbers to meet the grid specs.

## Color
All fonts on the website should use the specified grey called “grey-28” (#484848). Exceptions are:
- When used on dark background. In this case use white (#fff) instead
- Special cases