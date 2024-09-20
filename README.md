# My Portfolio Website

## Overview

This repository contains the source code for my personal portfolio website. The site showcases my skills, projects, and experiences with a responsive design that adapts to various screen sizes.

## Live Demo

You can view the live version of the website here:

[My Portfolio Website](https://yourdomain.com)

## Project Structure

The project consists of the following main files:

- **`index.html`**: The main HTML file that structures the website content.
- **`style.css`**: The primary stylesheet for styling the website.
- **`mediaqueries.css`**: Contains media queries for responsive design.
- **`script.js`**: JavaScript file for interactive features, such as the hamburger menu.

## `index.html`

The HTML file provides the basic structure of the website, including:

- Navigation bar
- Profile section
- About section
- Experience section
- Projects section
- Contact section

## `style.css`

The stylesheet includes:

### General Styles

- **Font and Reset**: Uses Poppins font from Google Fonts and resets margins and padding.
- **Transitions**: Smooth transitions for links and buttons.

### Navigation

- **Desktop Navigation**: Flexbox layout for desktop navigation with styles for links and the logo.
- **Hamburger Menu**: Styles for the responsive hamburger menu with transition effects.

### Sections

- **Profile Section**: Flex layout for profile picture and text.
- **About Section**: Flex layout for about containers with responsive adjustments.
- **Experience Section**: Flex layout for experience details with responsive adjustments.
- **Projects Section**: Styles for project containers and images.
- **Contact Section**: Flex layout for contact information with responsive styling.

### Buttons

- **General Button Styles**: Padding, border-radius, and hover effects for buttons.
- **Color Variants**: Different button styles and hover effects.

### Icons

- **General Icon Styles**: Cursor adjustments and hover effects.

### Footer

- **Footer Styles**: Centered text with specific height.

## `mediaqueries.css`

The media queries handle responsiveness for different screen sizes:

### For Screens Up to 1200px Wide

- **Navigation**: Hides desktop navigation and displays the hamburger menu.
- **Experience Section**: Adds top margin and adjusts layout.
- **Section Layout**: Changes section height and margin; makes section containers block-level.
- **Profile Picture**: Reduces size and adjusts margin.

### For Screens Up to 1400px Wide

- **Profile Section**: Adjusts height and margin.
- **About Containers**: Ensures containers wrap properly.

### For Screens Up to 600px Wide

- **Contact and Footer**: Increases height for better spacing.
- **Profile Section**: Adjusts height and margin.
- **Article Font Size**: Reduces font size.
- **Footer Navigation**: Adjusts height and margin.
- **Responsive Layouts**: Wraps containers and adjusts font sizes for better readability.
- **Section and Text Styling**: Adjusts image sizes and font sizes for smaller screens.

## `script.js`

### `togglemenu()` Function

- **Purpose**: Toggles the visibility of the hamburger menu on small screens.
- **Elements Affected**:
  - **Menu**: The `.menu-links` element that shows or hides menu items.
  - **Icon**: The `.hamburger-icon` element that changes appearance when the menu is open.
- **Functionality**: Adds or removes the `open` class to the menu and icon, causing the menu to slide open or closed and the icon to change its appearance.

## Usage

**Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/your-repository.git
