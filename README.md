# Price checker

This test requires that you to implement a product price checker interface.

![price_checker](https://user-images.githubusercontent.com/951477/33724379-36183f64-db67-11e7-9a6f-4728a36fb27b.jpg)

This widget should be a self-contained component that can placed within a larger
admin page - you can simply place it within a basic `index.html` page.

We have provided you with this bare-bones Django project to get started. Simply
fork this repo and begin working, ensuring that you install and add to the
requirements contained in `requirements.txt`.

The project contains:

1. The basic infrastructure to start running, with an sqlite DB
2. A `products` app containing two models - `Product` and `PricingBlock`
3. An initial data fixture to get going
4. A price search routine in `products.utils.get_price`
5. A simple unit test for `get_price`

The tasks you must carry out are as follows:

1. Optimise the `products.utils.get_price` function which is very long running
   under certain circumstances and contains faults
2. Implement the form as specified in the wireframe above using a modern
   javascript framework such as React, Vue or Angular
3. Please ensure the form is presentable - you may use a CSS framework like
   bootstrap or material-ui or roll your own
4. Hook up the interface to the backend, such that the user can find the
   cheapest price by specifying a product, start date and nights

Please provide us with information on how to run the code you provide.
