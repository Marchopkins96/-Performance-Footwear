# Performance Footwear

Welcome to Performance Footwear. This website is aimed at users who have a passion for running and the latest running shoes and accessories on the market. 
The site offers exclusive features for users that have an account with us, these include adding items to your wishlist to purchase in the future, viewing your order history, saving delivery preferences and adding reviews to products.
Users who visit the site are met with a user friendly experience, They can easily search for products, view products by category, add products to their bag/basket and make payment easily. There is also a section to send us a message, a privacy policy page and information about returning products.

[Link to Performance Footwear](https://performance-footwear-ed28bb401f1b.herokuapp.com/)

![Home Screen](documentation/readme_images/responsive.png)

<br>

# UX

## Strategy

### Target Users

- Running enthusiasts who have an active lifestyle and are interested in quality products.
- Users looking to browse and purchase running shoes and related accessories.
- Users who look for the top brands in the running shoe industry.

### Site Goals

- Allow users to view and purchase products as effortlessly as possible.
- Allow users to swiftly search for the products they like.
- Provide users with the option to create an account to store wishlist items and view orders.
- Allow users to store their preffered delivery address and be able to easily edit this.
- Offer users the ability to contact performance Footwear online.

### Peoject Goals

- Develop a fubctional e-commerce web application.
- Ensure users are met with a user-friendly interface to allow easy navigation around the site.
- Offer users a seamless shopping experience.
- Intergrate exciting features, such as a wishlist and customer reviews, enhancing CRUD functionality.

<br>

[Back to Top](#table-of-contents)

<br>

## **Agile Planning**

This project followed an agile planning approach, based on user stories. Each user story was carefully planned and included in a specific iteration.
To prioritize development tasks, each feature was catergorized as Must Have, Should Have, Could Have and Wont Have. Catergorizing each user story helped determine the importance of each feature.

View the project board [here](https://github.com/users/Marchopkins96/projects/7).

<details>
<summary> Project Board
</summary>

![Project Board](documentation/readme_images/user-stories.png)
</details>

## User Stories 

* Based on the user stories created, A project implementation plan was developed.
You can view the user stories [here](https://github.com/Marchopkins96/Performance-Footwear/issues?q=is%3Aissue+is%3Aclosed).

<details>
<summary> User Stories
</summary>

![User Stories](documentation/readme_images/issues-list.png)
</details>

* Using the MoSCoW principle (Must Have, Should Have, Could Have, Won't Have), iterations were planned for the implementation of the user stories.

View milestones [here](https://github.com/Marchopkins96/Performance-Footwear/milestones).

<details>
<summary> Milestones
</summary>

![Milestones](documentation/readme_images/iterations-list.png)
</details>

<br>

[Back to Top](#table-of-contents)

<br>

## Structure 

### Wireframes

- Wireframes have been created for all pages of the site. wireframes were crafted for mobile and desktop dimensions. [Balsamiq](https://balsamiq.com/) was employed as the tool for creating the site's wireframes.

### Home Page Wireframes

<details>
<summary>Click to View Home Page wireframes</summary>

#### Mobile
![screenshot](documentation/wireframes/wireframe-home-page-mobile-Large.png)


#### Desktop
![screenshot](documentation/wireframes/wireframe-home-page-desktop-Large.png)

</details>

### All Products Page Wireframes

<details>
<summary>Click to View All Products Page wireframes</summary>

#### Mobile
![screenshot](documentation/wireframes/wireframe-all-products-page-mobile-Large.png)


#### Desktop
![screenshot](documentation/wireframes/wireframe-all-products-page-desktop-Large.png)

</details>

### Product Detail Page Wireframes

<details>
<summary>Click to View Product Detail Page wireframes</summary>

#### Mobile
![screenshot](documentation/wireframes/wireframe-product-detail-mobile-Large.png)


#### Desktop
![screenshot](documentation/wireframes/wireframe-product-detail-desktop-Large.png)

</details>

### Basket Page Wireframes

<details>
<summary>Click to View Basket Page wireframes</summary>

#### Mobile
![screenshot](documentation/wireframes/wireframe-basket-page-mobile-Large.png)


#### Desktop
![screenshot](documentation/wireframes/wireframe-basket-page-desktop-Large.png)

</details>

### Checkout Page Wireframes

<details>
<summary>Click to View Checkout Page wireframes</summary>

#### Mobile
![screenshot](documentation/wireframes/wireframe-checkout-page-mobile-Large.png)


#### Desktop
![screenshot](documentation/wireframes/wireframe-checkout-page-desktop-Large.png)

</details>

### Contact Page Wireframes

<details>
<summary>Click to View Contact Page wireframes</summary>

#### Mobile
![screenshot](documentation/wireframes/wireframe-contact-us-mobile-Large.png)


#### Desktop
![screenshot](documentation/wireframes/wireframe-contact-us-desktop-Large.png)

</details>

### Wishlist Page Wireframes

<details>
<summary>Click to View Wishlist Page wireframes</summary>

#### Mobile
![screenshot](documentation/wireframes/wireframe-wishlist-mobile-Large.png)


#### Desktop
![screenshot](documentation/wireframes/wireframe-wishlist-desktop-Large.png)

</details>

### Edit Reviews Wireframes

<details>
<summary>Click to View Edit Reviews wireframes</summary>

#### Mobile
![screenshot](documentation/wireframes/wireframe-reviews-mobile-Large.png)


#### Desktop
![screenshot](documentation/wireframes/wireframe-reviews-desktop-Large.png)

</details>



### Database Schema 

- An entity relationship diagram (ERD) was created using [Lucid Chart](https://www.lucidchart.com/pages/tour). This allowed me to visually represent the connections between my data structures and streamlined the development. With this visual aid, it makes it much easier to understand and interact with my data.

![Database Schema](documentation/readme_images/erd-diagram.png)

[Back to Top](#table-of-contents)

<br>

## Main Plan 

- Design an inviting homepage that features eye catching images that convey the purpose of the site to the user.
- Implement user account registration to enable restricted access for editing and deleting reviews, adding products to a wishlist and saving personal user information to ensure quick and efficient checkouts.
- Develop a website that is responsive on a multitude of devices, ensuring optimum functionality across all screen sizes.
- Superusers harness the ability to create, view, update, and delete throughout the site.

<br>

# Features 

## Existing Features

### Home Page 
![Hero Image](documentation/readme_images/home-page-header.png)
- The Home page features a carousel of 3 images to instantly catch the attentions of the users visiting the site.

<br>

### Marketing Section
![Marketing section](documentation/readme_images/marketing-text.png)
- The marketing section is presented neatly in the middle of the homepage with more images relating to the sites purpose.
- Key words are used within the marketing text that link back to the brand name and also to aid search engine optimization.

<br>

### Footer 
![Footer](documentation/readme_images/footer.png)
- The footer is present on all pages of the site.
- It features links to contact, returns, privacy policy and links back to the home page.
- The footer also incorperates links to our MailChimp newsletter signup and a link to our FaceBook marketing page.

![Subscription](documentation/readme_images/subscription-success.png)

<br>

### Returns Page 
![Returns Page Image](documentation/readme_images/returns.png)

- Information of our returns policy is provided for users who desire to return items to us.

<br>

### Contact Page
![Contact Page Image](documentation/readme_images/contact-us.png)
- Contact information is presented in a clear and consise manner. The business phone number, address and email are displayed seperately at the top of the page.
- The page also includes a contact form enabling users to contact us. The message submitted by the user is stored in the admin panel.

<br>

### Privacy Policy
![Privacy Policy Image](documentation/readme_images/privacy-policy.png)
- A privacy policy is a legal document that describes how a website collects, uses, discloses and manages the personal information of its users or customers. It contains information about the types of data collected, the purposes for collecting it, storage and security methods, and the rights of users regarding their personal information.

<br>

[Back to Top](#table-of-contents)

<br>

### Main Nav Menu
![Nav](documentation/readme_images/free-delivery-banner.png)
![Nav](documentation/readme_images/strive-message.png)
![Nav](documentation/readme_images/free-returns.png)

- Displayed at the very top of the screen, there is information for the user regarding returns and delivery, as well as a phrase of motivation for visitors to the site.

![Main Nav Image](documentation/readme_images/main-nav-header.png)

- Consistent throughout the site, the user will see the main navigation menu. Featuring a search bar, account/profile access, basket link with subtotal if items are in the basket, as well as links to filter products by gender, brand, type of product and sale items. When a user creates an account they will also have access to the wishlist.

<br>

### Restricted Pages
![Logged in nav](documentation/readme_images/restricted-pages.png)

![Logged out nav](documentation/readme_images/logged-out-nav.png)

- Certain pages on the site are reserved exclusively for users who are logged in. Links to the these pages appear in the Navbar when a user is logged in.
- The wishlist functionality is for users who have a registered account with us.

<br>

### Product Filtration
![Main-nav Dropdown](documentation/readme_images/product-filtering.png)

- Users can filter products by gender, type of product, by brand and sale items.

![Filter](documentation/readme_images/sort-by.png)

- When on the products page users can filter the product by price, rating, name, category and brand.

<br>

### Search Bar
![Search Bar Image](documentation/readme_images/search-bar.png)

![Search product](documentation/readme_images/product-search.png)

![No result search](documentation/readme_images/no-results-search.png)

![Search Bar Error](documentation/readme_images/no-search-criteria.png)

- Users can use the search bar to search for specific products (first image above) that they want to view. The search is matched with the product name and description, as long as the search relates to a product it will show results.
- The user is also shown how many results meet their search (second image above).
- If search criteria does not relate to a product it will not return any results (third image above).
- If a user tries to search without inputting any search criteria an error is shown (fourth image above).

<br>

### Sale Page

![Sale image](documentation/readme_images/product-sale.png)

- This page displays all the sale products, it can also be filtered by gender.

<br>

### Product Details Page

![Product Detail Image](documentation/readme_images/product.detail-page.png)

- The product detail page displays the product image, name, regular price, sale price (if applicable), brand, category, rating, option to add to wishlist, product description, country of origin, materials, option to select size, select quantity and add product to cart.

![Country](documentation/readme_images/contry-dropdown.png)

![Materials](documentation/readme_images/materials-dropdown.png)

- Country of origin and Materials can be viewed when the dropdown menu is clicked by the user.

![Review not signed in](documentation/readme_images/review-not-signed-in.png)

- If the user is not signed in they are prompted to do so if they wish to leave a product review.

![Review product](documentation/readme_images/review-product.png)

- If the user is authorized. they can click on "Review this product" and a dropdown menu will appear.

![Review dropdown](documentation/readme_images/review-dropdown.png)

- Once clicked, the window opens and the user is able to write a review and hit the submit button.

![Review success](documentation/readme_images/review-success.png)

- When a review is submitted the user will see a success message telling them the review was submitted successfully.

![Review displayed](documentation/readme_images/review-displayed.png)

![Review edit](documentation/readme_images/edit-review.png)

- If a users wishes to do so they can edit their review.

![Review edit success](documentation/readme_images/review-updated.png)

- When the review is updated a success message is displayed to the user.

![Review delete](documentation/readme_images/delete-review.png)

![Review delete success](documentation/readme_images/delete-review-success.png)

- If a user decides they want to delete a review they can simply hit the delete review button.
- A success message is displayed once this action is complete.

![Back to Top Button](documentation/readme_images/back-to-top-button.png)

- To further add to a positive user experience a back to the top button has been added. It is located in the bottom right of the page and once clicked the user will be returned to the top of the given page.

<br>

[Back to Top](#table-of-contents)

### Wishlist Page
![Wishlist page](documentation/readme_images/wiahlist-with-product-added.png)
- The wishlist offers the users a place to store all the products that they like and may wish to purchase at a later date.
- The wishlist page provides the product image, name, description, regular or sale price and a link back to the product detail page.
- The page also has a delete button next to each individual product as well as "clear wishlist" button at the top of the page which empties everything from the wishlist if pressed.
- If a user is yet to add to their wishlist they will be met with the below message.

![Wishlist empty](documentation/readme_images/wishlist-empty.png)

- To add a product to your wishlist, you need to click on the love heart icon.

![Wishlist icon](documentation/readme_images/wishlist-icon.png)

- Once a product is successfully added to the wishlist a success message id displayed.

![Wishlist Success](documentation/readme_images/wishlist-success.png)

- If you click on the heart icon again, this will remove the item from the wishlist and a message will display to confirm this.

![Wishlist remove](documentation/readme_images/wishlist-remove-product-message.png)

- When on the wishlist page, if a user clicks on the binoculars icon this redirects you to the products page.
- You can remove an item from the wishlist by clicking the bin icon.

![Wishlist view remove](documentation/readme_images/view-or-remove-product-wishlist.png)


[Back to Top](#table-of-contents)

<br>


