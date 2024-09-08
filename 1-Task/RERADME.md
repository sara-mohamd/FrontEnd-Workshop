# Simple Webpage Project

This project is a simple multi-page website designed using HTML and inline CSS. It consists of a main **Home page** with links to other sections, including **About**, **Gallery**, **Staff**, and **Contact Us** pages. The styling is minimal and all pages share a consistent layout and navigation structure.

## Project Structure

The project includes the following HTML pages:

1. **Welcome.html** (Home Page)
2. **About.html** (About Page)
3. **Gallery.html** (Gallery Page)
4. **Staff.html** (Staff Page)
5. **Contact.html** (Contact Us Page)

The website is styled with basic inline CSS in the `<head>` section of each HTML file.

## Features

- **Home Page**: The main entry point of the website. Includes a header image, title, and links to other sections.
- **Navigation**: Each page contains navigation links allowing the user to switch between pages (Home, About, Gallery, Staff, Contact Us).
- **CSS Styling**: Basic CSS is applied to align text, set colors for links, and adjust the layout. Includes hover and visited states for navigation links.

## File Breakdown

- **Welcome.html**: 
    - Displays a large header image.
    - Contains navigation links to other pages.
    - Uses centered text alignment.
  
- **About.html**: 
    - Provides details about the website or company.
  
- **Gallery.html**: 
    - Displays images or multimedia content.
  
- **Staff.html**: 
    - Showcases team members or staff information.
  
- **Contact.html**: 
    - Includes contact information and possibly a form to reach out.

## Styling

All the pages share a similar style that includes:

- **Text Alignment**: The text is aligned to the center of the page.
- **Font Size**: The default font size is set to large for readability.
- **Link Colors**:
    - Default: Red
    - Visited: Blue
    - Hover: Light green with a pointer cursor.

## Assets

Images for the site should be stored in an `assets` directory, such as the `home.jpg` image used in the Home page.

Example for including images:
```html
<img src="../assets/home.jpg" style="margin-top: 0%; height: 390px; width: 1470px;" />
