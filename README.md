# E-Commerce Web Shop App

I've utilized this app from [JavaScript Mastery, ECommerce Web Shop](https://www.youtube.com/watch?v=377AQ0y6LPA&list=PL6QREj8te1P6wX9m5KnicnDVEucbOPsqR&index=5) video. Before telling about app, here is the link that I [published on netlify](https://e-commerce-by-emre.netlify.app/) and the gif that you can take a quick look through the app :

![Latest version](https://raw.githubusercontent.com/emreharman/e-commerce/master/src/assets/published.gif)

### 1. Cloning and Running App

    You can download this app to your local using `git clone https://github.com/emreharman/e-commerce.git` command on your bash. Then open your terminal in the folder that you cloned and open your command line, use `yarn install` command. This command will install all the dependencies that I use in the app. Finally use `yarn start` command to run the app.

### 2. About App

    This app is the simulation of an e-commerce site. You can enter a test credit card as I use on the gif, just keep pressing 4 and 2. I didn't use any database to store any information. I've used commerce.js to handle cart and checkout operations. Also I've stored the info's of products in the commerce.js. It's very useful to use commerce.js for storing your product's info's and i can handle all of cart and checkout operations.In this way, you don't need to write any backend or database or etc.

### 3. Dependencies

    In this app I've used ***Material UI***, ***Commerce.js***, ***Stripe.js***, ***React-Router*** and ***React-Hooks***.
    There are the commands that you can use to install these dependencies. (I've used yarn, you can use `npm install` instead of `yarn add` if you're using npm).

    - `yarn add @material-ui/core @material-ui/icons`
    - `yarn add @chec/commerce.js`
    - `yarn add @stripe/react-stripe-js @stripe/stripe-js`
    - `yarn add react-router-dom`
    - `yarn add react-hook-form`
