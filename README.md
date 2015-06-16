# futurama-planets

Scraped from : http://theinfosphere.org/List_of_planets with

```js
var list = []; 

$('#mw-content-text')
  .find('.mw-headline')
  .each(function()
  {
    list.push(this.outerText)
  });
```
