Optimizations for PageSpeed 
1. Added media="print" to print css
2. Added async to google anyalitics Javascript
3. Put portrait css for mobile in a separate file and set a media query for it.
4. Minified style.css and inlined it.
5. Optimized pizzeria image. 

Optimizations for main.js
1. Pulled the pizzasDiv var out of the loop so it's not called everytime the loop runs
2. Reduced number of background pizzas to 24
3. Pulled out phase and top vars from scrolling for loop so they won't need to be regenerated with each loop
4. Pulled var elem out of for loop so it's not generated everytime loop runs
5. Pulled movingPizzas var out of for loop and replaced document.querySelector with getElementById API
6. Replaced document.querySelectors with getElementById / getElementsByClassName
7. Created len var with randomPizzas.length so it's not calculated each loop
8. Saved items.length as a var so it's not run with each loop

To Run Portfolio
1. Download from Git Hub using your preferred method
2. Open p4_udacity directory
3. Left click index.html and open with your preferred browser

To Run Portfolio
1. Download from Git Hub using your preferred method
2. Open p4_udacity directory, then views directory
3. Left click pizza.html and open with your preferred browser