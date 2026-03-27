# Cat Cafe & Pilot Application Website

A dual-purpose web application built for CSC 356, featuring a cat cafe adoption page and a Mars pilot application form.

## Overview

This project consists of two interlinked websites:
- **Cat Cafe**: A welcoming homepage showcasing available cats for adoption
- **Pilot Application**: A form for applying to join as a pilot

## Features

- **Responsive Design**: Mobile-friendly layout with CSS styling
- **Form Validation**: JavaScript-based client-side validation for the pilot application form
- **Navigation Menu**: Shared menu component across all pages
- **Image Gallery**: Showcase of available cats for adoption

## Project Structure

```
1.1-csc356-fixed-main/
├── index.php        # Cat Cafe homepage
├── app.php          # Pilot Application form
├── menu.php         # Shared navigation menu
├── main.css         # Stylesheet for all pages
├── Java.js          # Form validation script
├── cats.jpg         # Cat image
├── babycats.jpg     # Baby cats image
├── catcafe.jpg      # Cafe image
└── README.md        # This file
```

## Files Description

| File | Purpose |
|------|---------|
| `index.php` | Home page - displays cat cafe information and adoption images |
| `app.php` | Application form page - collects pilot application data |
| `menu.php` | Shared navigation menu included in all pages |
| `main.css` | Central stylesheet for consistent styling across the site |
| `Java.js` | Client-side form validation and interactive features |

## Installation & Setup

1. **Prerequisites**: 
   - PHP 7.0 or higher
   - Web server (Apache, Nginx, etc.)

2. **Setup**:
   - Place the project files in your web server's root directory
   - Access `index.php` through your local server (e.g., `http://localhost/1.1-csc356-fixed-main/`)

## Usage

- **View Cat Cafe**: Navigate to `index.php` to browse available cats for adoption
- **Apply as Pilot**: Navigate to `app.php` to fill out the pilot application form
- **Menu Navigation**: Use the shared menu to navigate between pages

## Form Fields (Pilot Application)

- Full Name
- Home Address
- Experience with Animals
- Desired Cat Name
- Desired Cat Age

## Technologies Used

- **HTML5**: Page structure
- **CSS3**: Styling and layout
- **JavaScript**: Form validation
- **PHP**: Server-side includes (menu)

## Notes

- Form validation is performed on the client-side using JavaScript
- The menu component is included via PHP in all pages
- Images are stored locally in the project directory

## Author

School assignment for CSC 356
