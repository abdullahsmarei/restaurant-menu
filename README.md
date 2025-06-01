# restaurant-menu
Frontend implementation for the 'Savor the Moment' restaurant menu. This project showcases a responsive, multi-category food menu (including burgers, pizzas, and salads) built with HTML5 , CSS3 and JS. Designed to demonstrate clean code, semantic structure, and modern frontend practices for an intuitive user experience.

# Savor the Moment - Restaurant Menu UI

Savor the Moment is a responsive and visually appealing frontend for a restaurant menu application. This project demonstrates proficiency in HTML5 and CSS3 by creating an intuitive user interface with clean, semantic code and modern web design principles. It features distinct, browsable categories for an enhanced user experience.

## Table of Contents

* [Project Vision](#project-vision)
* [Key Features](#key-features)
* [Technology Stack](#technology-stack)
* [File Structure](#file-structure)
* [Live Preview & Setup](#live-preview--setup)
* [Visual Showcase](#visual-showcase)
* [License](#license)

## Project Vision

The core vision behind "Savor the Moment" is to deliver a seamless and engaging online menu experience. This frontend build prioritizes responsive design, ensuring accessibility across devices, and employs modern HTML5 and CSS3 practices to create a visually appealing and easy-to-navigate interface for restaurant patrons.

## Key Features

* **Intuitive Navigation:**
    * Features a main navigation bar with links to Menu, Category, About Us, and Contact pages.
    * Includes a shopping cart icon in the header for future e-commerce integration.
* **Dynamic Menu Display (`menu.html`):**
    * Items are logically categorized into Burgers ("Crafted to Perfection"), Pizza ("Baked with Passion"), and Salads ("Freshness Redefined").
    * Each food item is presented within an interactive card, showcasing an image, name, detailed description, price (in JD), and "More Details" / "Order Now" call-to-action buttons.
* **Efficient Category Navigation (`category.html`):**
    * A dedicated category page allows users to quickly navigate to specific menu sections (Burger, Pizza, Salad) using visually distinct cards that link to the respective parts of `menu.html`.
* **Responsive & Modern Design:**
    * Achieves a fully responsive layout using CSS3, ensuring optimal viewing and interaction on desktops, tablets, and mobile devices.
    * Leverages modern CSS techniques, including Flexbox for structuring layouts.
    * Enhanced user experience through subtle hover effects on cards, buttons, and navigation elements.
* **Consistent Branding & Styling:**
    * Maintains a consistent brand identity with the "Savor the Moment" title and logo prominently displayed in the header and footer.
    * Utilizes custom stylesheets (`style.css`) and Font Awesome icons for a polished and cohesive visual appearance.

## Technology Stack

This project is built exclusively with frontend technologies:

* **HTML5:** Semantic markup for structuring the content and layout.
* **CSS3:** Advanced styling, responsive design (Flexbox), and animations/transitions.
* **Font Awesome:** For scalable vector icons enhancing the UI.
* **JavaScript (`main.js`):** Linked for potential future interactivity and dynamic content rendering (specific functionalities are to be implemented).

## File Structure

The project is organized as follows:
savor-menu-ui/
├── menu.html               # Primary page displaying all food items, organized by category
├── category.html           # Landing page for users to select a food category
├── style.css               # Global stylesheet defining the visual appearance
├── image/                  # Directory for all visual assets
│   ├── logo.png            # Restaurant logo
│   └── webp/               # Sub-directory for optimized WebP images
│       ├── burger1.webp    # ... (burger images)
│       ├── pizza1.webp     # ... (pizza images)
│       ├── salad1.webp     # ... (salad images)
│       ├── cburger.webp    # ... (category images)
└── main.js  

## Live Preview & Setup

To explore this project locally:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/abdullahsmarei/restaurant-menu.git]

2.  **Navigate to the Directory:**
    ```bash
    cd restaurant-menu
    ```
3.  **Launch in Browser:**
    Open `menu.html` or `category.html` directly in any modern web browser.

## License

&copy; 2025 Savor the Moment. All rights reserved.
