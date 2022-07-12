# Undercut

e-Commerce website https://undercut-e-commerce.vercel.app/

## Description
The project built with NextJS. NextJS provides features like: navigation between pages, data fetching, dynamic routing. MongoDB and Mongoose to save and retrieve data like products, orders and users. The user has the following abilites:
* To see a product list
* To add products to cart
* Navigate to a product detail page
* Create user account, login/logout
* Сhange order in cart
* Pay order by PayPal(not use your real wallet)

## Setup

1. Clone the repo
```
git clone https://github.com/ialtytsev/undercut_e-commerce
```
2. Create a personal MongoDB database https://www.mongodb.com/atlas/database
3. Create .env file. Enter key to your database
```
MONGODB_URI = Enter key to your database
```
4. Navigate to server folder and install npm packages
```
cd server
npm i
```
5. Run `npm run dev` to start the app
