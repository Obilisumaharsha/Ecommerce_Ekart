### https://nextjs-ecommerce-typescript.vercel.app/

#### multi User Login System

- SignIn / SignUp ✔
- Forget Password ✔
- JWT validation on each Authorized Request ✔

# Customer

- View Product & Category ✔
- view product related to specific category ✔
- view dynamic pages detail with breadcamp ✔
- Add product to cart ✔
- Remove Product from cart ✔
- Increase Decrease cart Item Quantity ✔ (IF product Instock Quantity is less then your cart quantity then you are unable to increase that product Quantity)
- Alert if InStock Quantity isn't Available ✔
- Bookmark favourite Product ✔
- remove product from bookmark ✔
- Order a Product ✔
- After Creating an Order Product Exists in Cart for current User will be Cleared ✔
- track Order Status ✔
- View Order Detail ✔

## Tech

- Nextjs 13
- Typescript
- tailwind css
- Redux toolkit
- joi validation
- mongoDB

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`DB_URI` = Your mongoDB URL

`JWT_SECREAT` = Your custom JWT_SECREAT key

`NEXT_PUBLIC_API_BASE_URL` = Base URL for localhost => http://localhost:3000

## Installation

Install my-project with npm

```bash
  npm install
  npm run dev (for development server)
  npm run build (for Production)
  npm run preview (To View Production Server )

```
