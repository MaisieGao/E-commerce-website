Me and my teammates built a full-stack application using the MERN (MongoDB, Express, React, Node.js) stack.

The website we built is a e-commerce shopping website. 
It contains the home page that has a navbar, a search bar,three brands introduction, product best sellers and website contact info, the explore page that lists all the products the website have and can filter the product by brands or prices, the shopping cart page with the total amount calculated, the signin/signup page, user/admin dashboard pages depends on the users' indentities, create and manage products/brands pages for admin users, and a detail product page with a related list of product.

**For backend:**

*We connected mongodb database to our backend and created schemas that defined how data is organized within the database for the 3 database collections: categories, products, and users.
<br />
*We created routes to handle requests based on their different URLs and HTTP request methods. 
<br />
*We used api methods to handle requests and retrieve data from database and send the response back to the frontend.
<br />
*We seperated regular user from admin user.
<br />

**For Frontend:**
<br />
*We created functions to make GET,PUT,POST,DELETE requests to the API on the backend.
<br />
*On the home page, we had a search bar to filter needed products. We used styled-component library to displaying the three brands.
<br />
*We used Bootstrap library to create navbar, cards for products, cards for information in user dashboard.
<br />
*We created separate user interfaces for different roles in our website: the admin and the regular user. In the user dashboard page, the admin can add new brands and products to the website and manage the products while the regular users don’t have access to those data and can only see their own shopping cart info. We put the information that is entered by the admin in the database using frontend api methods to send and request data to the backend.
<br />
*We used local storage to store products in the cart and calculate the total price for checkout.
<br />
*We made the website responsive on different sized displays.

