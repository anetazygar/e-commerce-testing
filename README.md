# Exploring test for E-commerce Website
Link to website https://skleptest.pl/

# 📝Description
*A website dedicated to gaining skills in software testing.
Website for shopping clothes and accessories.*

# Functionality Tests ⬇️

## Main Page ##
  - Home page
  - Most wanted products
  - Categories
  - About Us
  - Contact
  - Blog

## Products Categories ##
  - Test any ability to sort products by name, price, size etc.
  - Test add to basket function

## Product Detail ##
  - Check product title
  - Check product description
  - Check product images
  - Test enlarge image function
  - Test add to basket function

## Product Search ##
  - Keyword search

## Shopping Cart / Basket ##
  - Add product(s) to shopping cart
  - Check display of product information, including
image, is correct in shopping cart
  - Adjust quantities of product in shopping cart
  - Remove product from shopping cart
  - Check relevant message displayed if no items
are in shopping cart
  - Check discounts, taxes and delivery costs are
correct (as applicable) in shopping cart
  - Check subtotal adds up correctly
  - Add a valid discount code (if applicable) and
check discount is applied correctly
  - Checkout process
    
## Subscription ##
  - subscribing to the newsletter

    
## Register form ##
- account registration - new user registration <br>
(test documentation in progress)

## Login ##
- user login
- password reminder
- password reset
- saving login details <br>
  (test documentation in progress)


# Bugs on e-commerce ⬇️
## Home Page ##
1. Photos not displayed correctly <a href= "https://drive.google.com/file/d/1xV4Smrj7ljvgBes2xJj5FteJ9izJ0mKB/view?usp=drive_link" target="_blank"> Check </a> 
3. You cannot enter the product description after clicking on the photo.
4. "Shop Now" and “Buy now” button on the home page redirecting to a non-existent page
5. The "Learn more" button redirects to a page with a contact form.
6. Arrows scrolling through products on the home page take the user to the top of the page
7. When width: 990px; the menu changes from horizontal to vertical, the vertical menu doesn’t work

## About Us ##
1. Clicking “About us” redirects you to the “Contact” website

   
## Contact ##
1. Google map is not displayed properly, visible is only link  <a href= "https://drive.google.com/file/d/1IQ0zCwz7EJ5s_tY_oFRkNrduRHq8_LIb/view?usp=drive_link" target="_blank"> Check </a> 
2. Unable to send a message via the contact form after entering the correct data - the message *"There was an error trying to send your message. Please try again later.”* <a href= "https://drive.google.com/file/d/1gX3NGBsC-13SAaUSaeX3DAZjfq17E1qR/view?usp=drive_link" target="_blank"> Check </a> 
3. The address of the contact reads “blabla” text https://skleptest.pl/test-contact-blablabla/ <a href= "https://drive.google.com/file/d/1MPoPdoXk33DGh6h0xXteB3M7KlKKeKXw/view?usp=drive_link" target="_blank"> Check </a> 


## Blog ##
1. After clicking on the menu “Blog” website, the message "nothing found" is displayed. <a href= "https://drive.google.com/file/d/1q_pETiAoOQP6vaMQZZYX2EHqbHjtG7NI/view?usp=drive_link" target="_blank"> Check </a> 
2. There are three search fields on the page
    - two search engines with magnifier
    - one search engine with the “Search” button


## Newsletter ##
1. You can subscribe to the newsletter by entering any character in the e-mail field.
   
## Most Wanted ##
1. The store logo is shifted to the right relative to the position on the home page <a href= "https://drive.google.com/file/d/1D3vjZGd2lswLJFE65ZlXyjmCU6nZTd4r/view?usp=drive_link" target="_blank"> Check </a> 
2. Items from the “Most wanted” can only be added to the cart in quantities of 99 or 100 pieces, after removing the minus sign in front of the quantity of products
3. Next adding 99 or 100 pieces of product to the cart causes its quantity to increase incorrectly


## Categories ##
1. Typo in the main panel "Catergries" instead of "Categories" <a href= "https://drive.google.com/file/d/1dEszmt8KTBoKk6IjXsGZCz9wnXDVeIBZ/view?usp=drive_link" target="_blank"> Check </a> 
2. In the drop-down menu, after displaying all products (ALL), most category photos are not displayed <a href= "https://drive.google.com/file/d/1Qao-7crPwUv8UJTV03qj-jYZDBzf1re5/view?usp=drive_link" target="_blank"> Check </a> 
3. The "Shoes" category also displays blouses <a href= "https://drive.google.com/file/d/1_qgF_SeePjTAklhAUs6Nuk-KwQGSB8O3/view?usp=drive_link" target="_blank"> Check </a> 
4. In the "Featured" category, the "Merchantile - Blouse" product is not centered on the page (the remaining products in the categories are centered) <a href= "https://drive.google.com/file/d/1nFsFl521OKEh8dfd5JGXRHMVeasZto9r/view?usp=drive_link" target="_blank"> Check </a> 


## Products ##
1. No option to choose product sizes  <a href= "https://drive.google.com/file/d/1IxTN01Z-P9UFaRjQycEUhE9gmfInnIs9/view?usp=drive_link" target="_blank"> Check </a> 
2. The right and left arrows to go to the next photo don’t work <a href= "https://drive.google.com/file/d/1XHcnHtryBIrS_EQSjR6asYbh8FsPFtY0/view?usp=drive_link" target="_blank"> Check </a> 
3. After displaying the photo doesn’t work
   - zoom in and out
   - close photo use “x” button
4. Product reviews are not displayed
5. Sorting by price (low-high and high-low) doesn’t work <a href= "https://drive.google.com/file/d/144J6nukH21MJsYNbZpyrtNydbTFDzqs8/view?usp=drive_link" target="_blank"> Check </a> 
6. After clicking "View cart" no action
7. You can only access the product description by placing the product in the cart and then going to the product card

## My Cart ##
1. On the home page, the price in the cart will only be updated after clicking "My Cart" in the upper right corner.
2. Product cannot be removed from cart using "X"
3. You can only remove a product by reducing its quantity to 0 and then updating your cart.
4. The "x" is not centered relative to the orange background <a href= "https://drive.google.com/file/d/1-6ryrTsKfbuXSq2cW7hlusJT4wicIsJv/view?usp=drive_link" target="_blank"> Check </a> 
5. After changing the quantity of the product in the cart (one or many) and clicking, the cart is updated BUT "-" and "+", which were used to change the quantity of products, also disappear <a href= "https://drive.google.com/file/d/1wf47cmer4_EsAZxqvWQ80bUqlcpUQv39/view?usp=drive_link" target="_blank"> Check </a> 
5. After updating the products in the cart to a 3-digit number, this value is not fully displayed in the "Quantity" field <a href= "https://drive.google.com/file/d/1DrQ_ywkaF5e3Dz2HNtB_S-W0wBXUUQBl/view?usp=drive_link" target="_blank"> Check </a> 



