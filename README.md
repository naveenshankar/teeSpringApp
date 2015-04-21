# Teespring Frontend Code Test
==============================

## Overview
Below is a small HTML/CSS/JS exercise that involves building out a part of a product page which involves a single product and it's variations.

Use SASS for css, but no other frameworks or libraries, no canvas. No JS plugins.

You can use the latest and greatest HTML5 and CSS3 features to build this out.

## Exercise
In index.html, rebuild the designs in the designs folder in Semantic HTML, CSS, and JS. The designs represent layouts in a smaller screen and a larger screen. It is not 2 pages.

### Specs:
- There are 40 variations to this product, each with a product id (use the products.json object).
- Each product has a single product image and title.
- When landing on the page initially, the first product should be selected.
- When clicking through the product selector, the single product image and title also updates.
- When clicking through each product selector thumbnail, the url updates with the product id. (http://{{page_url}}?id=5, if fifth product is selected)
- A url with http://{{page_url}}?id=5 should have the fifth product selected on page reload. The product selector should scroll to the 5th product thumbnail, 70px offset from the left.
- When clicking between product variations, hitting “Back” and “Forward” on the browser will also update the url, product image , and title according to the product id.
- The minimum width of the screen is 320px (640 @2x). The horizontal breakpoint is at 980px (1960px @2x). Built with a mobile first approach.

Pay attention details and the layout of the page. Keep it DRY.

Good luck!
