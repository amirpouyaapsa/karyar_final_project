# Bazarino \| Karyar Course Final Project · [README_FA](README_FA.md)

**Bazarino** is an e-commerce website design project developed using
HTML5 and CSS3 as the final project of the Karyar course. The goal of
this project is to design interconnected pages for a Persian online
store while following the principles of semantic HTML, user interface
design, responsive layout, and accessibility.

## Live Demo

**[View the Bazarino
Website](https://amirpouyaapsa.github.io/karyar_final_project/)**

Click the link above to explore the live version of the project.

## Project Pages

### 1. Products Page (`products.html`)

This page displays the products available in the Bazarino store and
includes the following sections:

-   A shared header containing the logo, main navigation menu, shopping
    cart indicator, and login link.
-   Breadcrumb navigation and a store introduction section.
-   A product filter form based on category, price range, and user
    ratings.
-   A product search field.
-   A sorting menu with options for newest, lowest price, highest price,
    and most popular.
-   Six product cards displaying product images, names, prices, ratings,
    and free-shipping labels where applicable.
-   Links from the product cards to their respective product details
    pages.
-   A shared footer containing the store tagline, relevant links, and
    copyright information.

### 2. Product Details Pages (`product_projector.html`, `product_iphone.html`, `product_headphone.html`, `product_Omega.html`, `product_kolah.html`, `product_laptop.html`)

The project includes six individual product details pages for the
Lonnovix projector, foldable iPhone, Onikuma gaming headset, Omega
Vision capsules, FM motorcycle helmet, and Surface Laptop 7. The pages
share a consistent layout and include the following features:

-   A shared website header and breadcrumb navigation.
-   A product image gallery with three product images and one main
    image.
-   A product badge, such as a bestseller label.
-   The product name, user rating, and number of reviews.
-   Product description and feature information.
-   Product price and an Add to Cart button.
-   Stock availability and estimated shipping information.
-   A customer reviews section containing reviewer names, ratings, and
    review text.
-   A shared footer consistent with the other pages.

### 3. Registration Page (`register.html`)

This page provides a user account creation form and includes the
following features:

-   The shared website header.
-   A registration card with a title and description.
-   An email field with HTML email validation.
-   A mobile phone field with a validation pattern for Iranian mobile
    numbers.
-   A password field with a minimum length of 8 and a maximum length of
    64 characters.
-   A password confirmation field.
-   Submit and Clear buttons.
-   HTML attributes for basic form validation and autocomplete.
-   A shared footer consistent with the other pages.

## Technologies and Tools Used

-   **HTML5:** Structuring pages, using semantic elements, and creating
    forms.
-   **CSS3:** Designing the user interface, styling components, and
    arranging page sections.
-   **Flexbox and CSS Grid:** Organizing layouts and aligning page
    elements.
-   **CSS Variables:** Managing shared design values such as colors,
    spacing, border radii, and shadows.
-   **CSS Reset:** Normalizing browser default styles using the
    `reset.css` file.
-   **Persian Font:** Using the local Vazirmatn variable font to improve
    the readability of Persian content.
-   **Responsive Design:** Adapting the store layout to different screen
    sizes using CSS media queries.
-   **Dark Mode:** Supporting the system color scheme through the
    `prefers-color-scheme: dark` media query.
-   **Git and GitHub:** Version control and project repository hosting.

## Technical Features

-   Support for the Persian language and right-to-left text direction
    (`RTL`).
-   Use of semantic HTML elements such as `header`, `nav`, `main`,
    `section`, `article`, `aside`, and `footer`.
-   Use of labels associated with form fields to improve accessibility.
-   Alternative text for product images using the `alt` attribute.
-   Use of form validation attributes such as `required`, `pattern`,
    `minlength`, and `maxlength`.
-   A consistent header, main navigation, and footer design across the
    pages.
-   Separate CSS files for the products page, product details pages, and
    registration page.
-   Responsive layouts, including product grids that adapt to smaller
    screens.
-   Reusable CSS custom properties for colors, spacing, border radii,
    and shadows.
-   Hover and focus states for interactive elements.
-   Local product images and a local Vazirmatn font file.
-   Dark-mode styling based on the user's operating-system preference.

## Project File Structure

``` text
Bazarino/
│
├── products.html
├── product_projector.html
├── product_iphone.html
├── product_headphone.html
├── product_Omega.html
├── product_kolah.html
├── product_laptop.html
├── register.html
│
├── css/
│   ├── reset.css
│   ├── style_products.css
│   ├── style_product.css
│   └── style_register.css
│
├── font/
│   └── Vazirmatn[wght].woff2
│
├── assets/
│   ├── iPhone_Duo_eSIM01.webp
│   ├── iPhone_Duo_eSIM02.webp
│   ├── iPhone_Duo_eSIM03.webp
│   ├── Lonnovix01.webp
│   ├── Lonnovix02.webp
│   ├── Lonnovix03.webp
│   ├── OmegaVision01.webp
│   ├── OmegaVision02.webp
│   ├── OmegaVision03.webp
│   ├── Onikuma01.webp
│   ├── Onikuma02.webp
│   ├── Onikuma03.webp
│   ├── Red_line_FM01.webp
│   ├── Red_line_FM02.webp
│   ├── Red_line_FM03.webp
│   ├── Surface_Laptop_701.webp
│   ├── Surface_Laptop_702.webp
│   └── Surface_Laptop_703.webp
│
├── README.md
└── README_FA.md
```

The file and folder names above reflect the current project structure
and the local asset references used by the pages.

## How to Run the Project

Since the project is built with HTML and CSS, it does not require any
dependencies or a server setup for basic execution.

1.  Clone the project repository from GitHub or download it.
2.  Keep the HTML files alongside the `css`, `font`, and `assets`
    directories, preserving their relative paths.
3.  Open `products.html` in a web browser.
4.  Navigate to the product details and registration pages using the
    links in the website.

## Limitations of the Current Version

This project is a front-end user interface prototype. In its current
version:

-   Search, filtering, and sorting are not connected to functional
    client-side logic.
-   Adding products to the shopping cart does not have actual
    functionality.
-   Registration is not connected to an authentication system or
    database.
-   Matching the password and password confirmation fields requires
    custom validation.
-   Links defined with `#` have not yet been connected to actual pages
    or functionality.

## Educational Objective

This project was developed to apply HTML and CSS concepts in a practical
e-commerce website and serves as the final project of the Karyar course.
The implementation focuses on semantic page structure, form design,
responsive layouts, reusable CSS, accessibility basics, and creating a
consistent user interface.

------------------------------------------------------------------------

**Project Name:** Bazarino\
**Project Type:** Karyar Course Final Project\
**Field:** Web User Interface Design\
**Technologies:** HTML5 and CSS3\
**Interface Language:** Persian (RTL)
