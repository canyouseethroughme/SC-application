# MY SOLUTION

## Features
- view store items
- add items to cart
- manage cart 


## How it works

I have a mock database in the form of a JSON file. For the shop page, I fetch the items from the JSON file and display them on the page. Every "Add to cart" button has a click handler, which takes care of adding the item to cart. On every cart interaction, it is synced with `localStorage` for persistance. 
The cart page displays the items and buttons for managing quantity or removing the item from cart. 
