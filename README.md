## Udacity FEND Project 4: Website Optimization

### Summary

This project required improving the loading and rendering of an existing portfolio site. The loading and rendering time of the site were measured using Chrome Dev tools and the bottle necks were removed.

To get started, check out the repository and inspect the code.

#### Part 1: index.html

The changes made to index.html were:

1. Added the styling from style.css into the index.html
2. Added the attribute media="print" for the print style. This takes it off the CRP.
3. Made the call to google analytics and js/perfmatters async as they arnt necessary for loading and rendering of the page.
4. Loaded the font using WebFontConfig.
5. Moved the call to google analytics to the bottom of the page.

### Part 2: main.js and pizza.html

The changes made to pizza.html were:
 
1. The pizzaria.png was to large for the space it ocupied so it was scalled down.

The changes made to main.js were:

1. Removed the dx function and put it inside the changePizzaSizes function.
2. Referenced all the variables outside a loop only updated the view inside the loop.

