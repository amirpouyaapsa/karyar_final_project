# Bazarino | Karyar Course Final Project · [README_FA](README_FA.md)

**Bazarino** is an e-commerce website design project developed using HTML5 and CSS3 as the final project of the Karyar course. The goal of this project is to design three interconnected pages of a Persian online store while following the principles of HTML structure, user interface design, responsive layout, and accessibility.

## Live Demo

**[View the Bazarino Website](https://amirpouyaapsa.github.io/karyar_final_project/)**

Click the link above to explore the live version of the project.

## Project Pages

### 1. Products Page (`products.html`)

This page displays the products available in the Bazarino store and includes the following sections:

- A shared header containing the logo, main navigation menu, shopping cart, and login link.
- A breadcrumb navigation.
- A store introduction section.
- A product filter form based on category, price range, and user ratings.
- A product search field.
- A sorting menu with options for newest, lowest price, highest price, and most popular.
- Six products displayed as product cards, each containing an image, name, price, and rating.
- A shared footer containing the store description, relevant links, and copyright information.

### 2. Product Details Page (`product.html`)

This page displays detailed information about the "FM Model Motorcycle Helmet" and includes the following features:

- Breadcrumb navigation.
- A product image gallery with three thumbnails and one main image.
- A "Best Seller" badge.
- The product name, user rating, and number of reviews.
- Product description and feature information.
- Product price and an Add to Cart button.
- Stock availability and estimated shipping time.
- A customer reviews section containing reviewer names, ratings, and review text.
- A header and footer consistent with the other pages.

### 3. Registration Page (`register.html`)

This page provides a user account creation form and includes the following features:

- The shared website header.
- A registration card with a title and description.
- An email field with input type validation.
- A mobile phone field with a validation pattern for Iranian mobile numbers.
- A password field with a minimum length of 8 and a maximum length of 64 characters.
- A password confirmation field.
- Submit and Clear buttons.
- HTML attributes for basic form validation.
- A shared footer consistent with the other pages.

## Technologies and Tools Used

- **HTML5:** Structuring pages, using semantic elements, and creating forms.
- **CSS3:** Designing the user interface, styling components, and arranging page sections.
- **Flexbox:** Organizing layouts and aligning page elements.
- **CSS Reset:** Normalizing browser default styles using the `reset.css` file.
- **Persian Font:** Using a Persian font to improve the readability of the website content.
- **Git and GitHub:** Version control and project repository hosting.

## Technical Features

- Support for the Persian language and right-to-left text direction (`RTL`).
- Use of semantic HTML elements such as `header`, `nav`, `main`, `section`, `article`, `aside`, and `footer`.
- Use of labels associated with form fields to improve accessibility.
- Alternative text for product images using the `alt` attribute.
- Use of form validation attributes such as `required`, `pattern`, `minlength`, and `maxlength`.
- Consistent header, main navigation, and footer design across all three pages.
- Separate CSS files for each page to improve style management.
- Use of local images to display products.

## Project File Structure

```text
Bazarino/
│
├── products.html
├── product.html
├── register.html
│
├── css/
│   ├── reset.css
│   ├── style_products.css
│   ├── style_product.css
│   └── style_register.css
│
├── assets/
│   ├── Epson.webp
│   ├── iPhone_Duo_eSIM.webp
│   ├── Nova_Pro_Omni.webp
│   ├── Omega_3.webp
│   ├── Red_line_FM01.webp
│   ├── Red_line_FM02.webp
│   ├── Red_line_FM03.webp
│   └── Surface_Laptop_7.webp
│
└── README.md
```

This structure represents the suggested organization of the project files based on the paths used in the HTML. If a local font file is used, a fonts directory should also be added to the structure.

## How to Run the Project

Since the project is built with HTML and CSS, it does not require any dependencies or a server setup for basic execution.

1. Clone the project repository from GitHub or download it.
2. Place `products.html`, `product.html`, and `register.html` alongside the `css` and `assets` directories.
3. Open `products.html` in a web browser.
4. Navigate to the other pages using the links in the header and product cards.

## Limitations of the Current Version

This project is a front-end user interface prototype. In its current version:

- Search, filtering, and sorting are not connected to functional client-side logic.
- Adding products to the shopping cart does not have actual functionality.
- Registration is not connected to an authentication system or database.
- Matching the password and password confirmation fields requires custom validation.
- Links defined with `#` have not yet been connected to actual pages or functionality.

## Educational Objective

This project was developed to apply HTML and CSS concepts in a practical e-commerce website and serves as the final project of the Karyar course. The implementation focuses on proper page structure, form design, semantic HTML elements, Flexbox layouts, and creating a consistent user interface.

---

**Project Name:** Bazarino  
**Project Type:** Karyar Course Final Project  
**Field:** Web User Interface Design  
**Technologies:** HTML5 and CSS3  
**Interface Language:** Persian (RTL)
