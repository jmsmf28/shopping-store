# React Shopping Cart

# Step 1: Create React App
# 13 Add Redux to Cart
    1. Update task and branch
    2. types.js
    3. create ADD_TO_CART
    4. create REMOVE_FROM_CART
    5. actions/cartActions.js
    6. create addToCArt
    7. create removeFromCart
    8. reducers/cartReducers.js
    9. case ADD_TO_CART
    10. case REMOVE_FROM_CART
    11. Cart.js
    12. connect props: cartItems
    13. connect actions: removeFromCart
    14. Product.js
    15. add action addToCart
    16. App.js
    17. remove Cart props
    18. store.js
    19. set initial cartItems to localStorage
    20. check result
    21. update task and branch
# 14 Create Order
    1. Backend
    2. server.js
    3. create order model
    4. get /api/orders
    5. post /api/orders
    6. delete /api/orders/:id
    7. Frontend
    8. create types
    9. types.js
    10. CLEAR_ORDER, CLEAR_CART, CREATE_ORDER
    11. create actions
    12. actions/orderActions.js
    13. createOrder(order)
    14. clearOrder()
    15. create reducers
    16. reducers/orderReducers.js
    17. case CREATE_ORDER
    18. case CLEAR_ORDER
    19. Update Cart Component
    20. components/Cart.js
# 15 Manage Orders
    1. 
    2. Add Amin Secrion
        1. Add new page
        2. Install react-router-dom
        3. App.js
        4. Import BrowserRouter, Route, Link
        5. render()
        6. BrowserRouter
        7. Route path="/admin" component={AdminScreen}
# 16 Deploy on Heroku
# 17 Changes to do
    1. add stock
    2. when an order is confirm update the stock.
    3. if stock = 0 the product doesn`t shows ???
    4. implement sort by type (for instance: women clothes, women shoes, sports, etc..)
    5. add home, about us, contact page
    6. add multiple images
    7. add selection of size when you click on the button add to cart
    8. add paypal payments
    9. send email with order confirmation
    10. add freight charges
    11. update backend (security and more)