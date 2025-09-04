# HSL WordPress UI Project

This project contains static HTML pages designed for a WordPress UI. The pages are structured to be easily converted into a WordPress theme.

## Pages

- index.html: Home page
- about-us.html: About Us page
- service.html: Services page
- products.html: Products page
- contact.html: Contact page
- service-area.html: Service Area page

## Structure

- header.html: Reusable header with navigation
- footer.html: Reusable footer
- styles.css: CSS styles for the site

## Usage

Open any HTML file in a web browser to preview the UI.

## Uploading to WordPress

To convert this to a WordPress theme:

1. Create a new theme folder in wp-content/themes/
2. Copy the HTML structure into PHP files (e.g., header.php, footer.php, index.php)
3. Replace static content with WordPress functions (e.g., wp_nav_menu for navigation)
4. Add functions.php for theme functionality
5. Activate the theme in WordPress admin

## Notes

- Header and footer are included via JavaScript fetch for reusability in static HTML.
- In WordPress, use get_header() and get_footer() instead.
