# Super Simple CSS Tooltips
Easily add a tooltip hover effect to the left, right, and bottom of an element. A second bottom option includes a triangle pointer.

![image of tooltip](https://github.com/AllThingsSmitty/super-simple-css-tooltips/blob/master/img/tooltip.png)

###CSS Classes
* `tooltip--left`
* `tooltip--right`
* `tooltip--bottom`
* `tooltip--triangle`

The CSS creates a tooltip specific to the element's `data-tooltip` attribute. 

###Text
```html
<p class="tooltip--left" data-tooltip="What does this even mean?!">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
```
###Buttons
```html
<button class="tooltip--right" data-tooltip="Made 'ya click!">I'm a happy button</button> 
```
###Links
```html
<a href="https://github.com/AllThingsSmitty/super-simple-css-tooltips" class="tooltip--triangle" data-tooltip="Ha, ha! Yeah boyyy!">Click it, cuz you know you want to!</a>
```
