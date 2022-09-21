# Team:Pink Pacific - Cosmetic Website

This project is designed for users to view and search for cosmetics, check for product descriptions ,shop and check out the items in the shopping cart. 
Team member: Yuan Liu, Shuyue Gao, Ye Zhang

## Iter 2

**Project contribution:**

Shuyue Gao created the AddCategory page and AddProduct page to make the authorized users (Admins) to submit forms with required fields (some updates on the backends to make sure every field is filled out properly with restrictions) to create brands and create products from the website/frontend. Shuyue also created the card.js to design what kinds of information of each product should appear on the card (Whether the product is in stock, view product button to direct customers to product detailed page, and add to cart button to add to cart). Shuyue also created the detailed product page to show customers detailed information about each product and the product's related products. Shuyue added showImage.js to make sure each image is showing properly and created the home page that could show the best selling products. Shuyue added the routes needed, created style.css, menu.css, search.css, showimage.css,layout.css and card.css. Shuyue add the logo on the navbar and change the design, background color for the navbar and the layout. Shuyue also added a font that is used for the entire website.

Yuan Liu created the shop page and added shop page in the menu. Yuan also implemented the filters in the shop page, including filter by brand and filter by price range, so that users can filter the products base on the brand they want to look at and the price range of the product. Those filters are located in the side bar, users can use those filters by clicking on the checkboxes. Yuan also set up the controller methods and routes on the backend so that the frontend can make a request to the backend to fetch desired products based on the filters. Yuan then set up frontend to display the fetched products on the shop page as well as implemented the “load more” botton. In addition, Yuan implemented the frontend component for search bar and created route and controller methods in the backend for the search bar. The search bar allows users to pick a desired brand and type out the search query in the search box to search for specific items. Also, Yuan added search messages to show number of results for the search. Yuan also worked on fixing some css style issues in the frontend.

Ye Zhang finished the set ups for the backend, including setting up the routes for admin and for registered users and handleded the authentication for the admin and users. For the admin, Ye created the functions for admin to add category and add products. For registered users, Ye created the functions for users to signin, signup and add products to shop cart. Ye also tested the backend apis using postman. For frontend, Ye created the page for user signin, signup, signout and handled user success and error. Saved user information to local storage. Ye also created user dashoard component and admin dashboard component. Added proper links to dashboard based on user's role. For admin, Ye setted private routes so that he/she can go to the page for adding categories and products. For users, he/she can update information and view the shopping cart. 

<hr>

**Screenshots**

1. Home page:
<br>

![one](./screenshots/home.png)
<br>

2. Shop page:
<br>

![two](./screenshots/shop.png)
<br>

3. User signup page:
<br>

![three](./screenshots/signup.png)
<br>

4. User signin page:
<br>

![four](./screenshots/signin.png)
<br>

5. User dashboard:
<br>

![five](./screenshots/user_dashboard.png)
<br>

6. Admin dashboard:
<br>

![six](./screenshots/admin_dashboard.png)

7. Admin add category page:
<br>

![six](./screenshots/admin_add_category.png)

8. Admin add product page:
<br>

![six](./screenshots/admin_add_product.png)

9. MongoDB categories:
<br>

![six](./screenshots/mongodb_categories.png)

10. MongoDB products:
<br>

![six](./screenshots/mongodb_products.png)

11. MongoDB users:
<br>

![six](./screenshots/mongodb_users.png)

<hr>

## Iter 1

**Project contribution:**

Shuyue Gao created different routes for products and category/brand, generate several methods to find, create, read, update, delete products and category/brand when admin user is logged in (created middlewares to restrict access for different roles) and connect the methods to different routes for the backend. Shuyue Gao define the products and category/brand schema, added virtual fields and methods to the schema. Shuyue Gao also deployed the project onto heroku and designed the website logo.

Yuan Liu defined the user schema, added virtual fields and methods to the schema to encrypt the password and authenticate the user. Worked on the routes and controllers for signup, signin and signout, and the validation of the input signin information. Also created middlewares to restrict access for different roles in this website: the website admin, customers who have logged in and customers who are not logged in. Yuan Liu also set up the cluster on MongoDB Atlas and made deployments on heroku.

Ye Zhang set up the backend of this project using node JS and installed the necessary dependencies. Initially connected this project to MongoDB and gitpush to group github. For frontend part, Ye Zhang created a frontend react app. Set up the structure of the frontend, including user signup page, signin page and home page. Set up 3 routes linked to signup page, signin page and home page. Added menu bar and shared the layout component to all the pages. Worked on the signup page to create a signup form and leveraged useState Hook to handle change.

<hr>

**Screenshots**

1. a display of my project backend file tree:
<br>

![one](./screenshots/screenshot1.png)
<br>

2. a display of my project frontend file tree:
<br>

![two](./screenshots/screenshot2.png)
<br>

3. heroku home page:
<br>

![three](./screenshots/heroku_home.png)
<br>

4. heroku signup page:
<br>

![four](./screenshots/heroku_signup.png)
<br>

5. backend connected to db screenshot:
<br>

![five](./screenshots/db_connected_backend.png)
<br>

6. the cluster on MongoDB Atlas:
<br>

![six](./screenshots/mongodb_atlas.png)