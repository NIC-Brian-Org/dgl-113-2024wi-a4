# DGL 113 2024WI Assignment #4

Create a new file in the `docs` folder called `app.js`.

At the top of the `docs/app.js` file, add the `use strict` directive:

```javascript
'use strict';
```

Add a `<script>` element to the `index.html` file to include the `app.js` script.
Place the `<script>` element just before the closing `</body>` tag just like
the script element that is used to include the `main.js` script.

Create the following functions:

- `addItem(quantity,size,description)`: adds an item to the drink order.
- `deleteItem(index)`: deletes the item at position `index` in the drink order.
  `index` is 0-based, so 0 means the first item, 1 means the second item, and
  so on.
- `getOrderTotal()`: calculates the total cost of the drink order.
  Short, Tall, Grande, and Venti coffees cost 2.99, 3.19, 3.49 and 3.99 respectively.
  Short, Tall, Grande, and Venti teas cost 2.85, 3.05, 3.25, and 3.50 respectively.

You should maintain all informaiton about the order using several arrays.
The `getOrderTotal()` function should be implemented by iterating over
those arrays.

You may have to create some global variables and/or constants to solve this problem.

NOTE: Only modify the `docs/app.js` and `docs/index.html` files. Do not make changes to any other files.
