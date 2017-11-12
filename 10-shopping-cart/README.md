# SHOPPING CART
For this project you will create a basic shopping cart application. The application will have a home page, product pages, and a shopping cart page. The user will be able to add and remove items from a shopping cart.

## SPECIFICATIONS
  * You have complete creative freedom with this application to make it look however you see fit. However the end result should, at a minimum, meet the following specifications.

  * Your application should function as a [single-page application](https://en.wikipedia.org/wiki/Single-page_application). Meaning, navigating between pages should not result in a page refresh.

    * Client-side routing to different "pages" or "views" can be tough. Here are some ideas on how to accomplish this:
        * window.location.hash
        * history.pushState
        * [Navigo](https://github.com/krasimir/navigo) (*my example uses this*)
        * [History.js](https://github.com/browserstate/history.js/)

    * Your implementation of client-side routing should not break the back and forward buttons in the browser.

    * Add transitions between pages when changing the route.

  * **ALL PAGES**:

    * All pages must display a site logo and navigation bar. The navigation bar should give the user the option to navigate back to the home page or to the shopping cart page.

    * An active navigation item should stand out depending on the current page or view.

    * The shopping cart navigation item should display the number of items currently in the shopping cart. The number of items should increment or decrement when an item is added or removed from the cart.

  * **HOME PAGE**:

    * The home page should display a list of all products.

    * Each product must include a button to add the item to the shopping cart.

    * Each product, when clicked, will navigate the user to view more details about that particular product (product page).

  * **PRODUCT PAGE**:

    * The product page should display more details about a particular product.

    * At a minimum there should be a product image, description, price, and an add to cart button.

    * When the add to cart button is clicked, the product is added to the shopping cart.

  * **SHOPPING CART PAGE**:

    * The shopping cart page will display all items currently in the shopping cart. If there are no items, it will display a message indicating the shopping cart is empty.

    * When there are items in the shopping cart, each item name should be clickable to navigate back to the individual product page for the selected product.

    * Each item in the cart should include a button to remove the item from the cart.

    * Use localStorage to save the shopping cart so that if the user leaves and returns at a later date, the items they have added to their cart will still be in their cart.

## EXTRA CREDIT
  * Use AJAX to asynchronously load shop products from a JSON file. The AJAX method you use to asynchronously load shop items is up to you.

      * *Note:* You will need to be running a local web server to accomplish this.
      
  * The entire application should be responsive and mobile friendly.

## EXAMPLE
[Here is an example](https://codepen.io/tophergates/full/EwGZNg/) of how this might look. **DO NOT LOOK AT THE SOURCE CODE! THAT'S CHEATING!!**
