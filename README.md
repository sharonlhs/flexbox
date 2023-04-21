#Flexbox

[Resources](https://web.archive.org/web/20230327153805/https://www.internetingishard.com/html-and-css/flexbox/)

Flexbox gave us a ton of amazing new tools for laying out a web page. Compare these techniques to what we were able to do with floats, and it should be pretty clear that flexbox is a cleaner option for laying out modern websites:

Use `display: flex`; to create a flex container.
Use `justify-content` to define the horizontal alignment of items.
Use `align-items` to define the vertical alignment of items.
Use `flex-direction` if you need columns instead of rows.
Use the `row-reverse` or `column-reverse` values to flip item order.
Use `order` to customize the order of individual elements.
Use `align-self` to vertically align individual items.
Use `flex` to create flexible boxes that can stretch and shrink.

Auto-margins eat up all the extra space in a flex container, so instead of distributing items equally, this moves the `.signup` and any following items `(.login)` to the right side of the container. 
