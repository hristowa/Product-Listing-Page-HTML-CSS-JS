Overview

The Cat and Dog Food Online Shop project is a simple website designed to offer a user-friendly online shopping experience for pet owners looking to purchase food for their cats and dogs. The project has been implemented using HTML, CSS, and JavaScript without the use of any frameworks.

Features
1. Sticky Navigation Menu

The website features a sticky navigation menu that remains fixed to the top of the screen as the user scrolls, ensuring easy access to important links and sections.

2. Home Page

The home page is designed with simplicity in mind. It displays images linked to product categories, providing an intuitive way for users to navigate to their desired section.

3. Static Footer

The footer remains static throughout the website and contains essential information about the online shop. Additionally, it includes social media links for contact and engagement.

4. Cat Paw Pop-up

As users scroll to the bottom of the page, a playful pop-up image of a cat paw appears. When clicked, it disappears, adding a delightful touch to the user experience.

5. Product Pages

The product pages feature the same sticky navigation menu found on the home page. The header provides information about the products available.

6. Sorting Function

The product pages offer a sorting function to arrange products based on user preferences. Sorting options include alphabetical A-Z, Z-A, Price Ascending, and Price Descending. Additionally, users can select "Choose" for neutral sorting.

7. Filtering Function

The left side of the product pages includes a filtering function. Users can filter products by brand, rating stars, and type of food.
Multiple brands, ratings ranging from 1 to 5 stars, and food types (dry, canned, snacks) are available for filtering.

8. Data Handling with JSON

All product data is stored in objects within a JSON file. The website fetches this data to display products dynamically. Images are stored in a separate folder and linked to the JSON file.

9. Product Grid

Products are displayed in a grid-like card layout, including product images, brand and name, rating, product type, price, and an "Add to Cart" button. Clicking the "Add to Cart" button triggers an alert.

10. Responsive Design

The website is designed to be responsive, adapting to different screen widths. The product grid layout changes accordingly to provide the best user experience across devices.

11. Product Counter

At the end of the product grid on the right side, a product counter displays the total number of products currently shown on the page.


Code Structure
1. HTML

    index.html: Home page of the website with linked category images.
    cat_food.html and dog_food.html: Product pages for cat and dog food.

2. CSS

    styles.css: Contains styling for the navigation menu, home page, and footer.
    product_styles.css: Contains styling specific to the product pages.

3. JavaScript

    index.js: Contains shared JavaScript functions.
    cat_food_script.js and dog_food_script.js: JavaScript files for cat and dog food pages. The fetching data function is different in each file due to different data sources.

Note

The "Load more" button has not been included in the project due to issues with the filter function. Instead, all products are displayed to ensure the filter works as expected.

![home-page](https://github.com/hristowa/Product-Listing-Page-HTML-CSS-JS/assets/119531049/4c79fe56-c7b5-4edb-bd83-434b566b2e4b)
![home-page2](https://github.com/hristowa/Product-Listing-Page-HTML-CSS-JS/assets/119531049/137b9a8b-d8b0-406f-8fff-e19f9cb95c62)
![product-page](https://github.com/hristowa/Product-Listing-Page-HTML-CSS-JS/assets/119531049/d18621b6-5da5-4d32-b208-f25d5ab23e53)

![product-page2](https://github.com/hristowa/Product-Listing-Page-HTML-CSS-JS/assets/119531049/36bf4e93-6961-4bdd-a21b-83162a1be633)
![product-page3](https://github.com/hristowa/Product-Listing-Page-HTML-CSS-JS/assets/119531049/507c8979-a0c9-4ea7-9849-ba6a63191f50)

![roduct-page4](https://github.com/hristowa/Product-Listing-Page-HTML-CSS-JS/assets/119531049/be9aae9b-38f4-4d44-85d1-7e567c65e6d1)



