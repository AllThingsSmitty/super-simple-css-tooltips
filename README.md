# Super Simple CSS Tooltips

Easily add a tooltip hover to an element. The tooltip hover can be placed to the left, right, or bottom of an element. A second bottom option includes a pointer.

![image of tooltip](https://github.com/AllThingsSmitty/super-simple-css-tooltips/blob/master/img/tooltip.png)

### CSS Classes

* `tooltip--left`
* `tooltip--right`
* `tooltip--bottom`
* `tooltip--triangle`

### Usage

The CSS takes any element that has a `tooltip--*` class and uses the `data-tooltip` attribute on the element to provide the tooltip text.

```css
[class^="tooltip"] {
  ...
  content: attr(data-tooltip);
  ...
}
```

```html
<img href="/img/info.svg" class="tooltip--left" data-tooltip="This is the text displayed">
```

### Support

Current versions of Chrome, Firefox, Safari, Edge, and IE10+.