# CodeCraft Blog

A modern, responsive blog website focused on web development topics with interactive features.


## Features

- **Responsive Design**: Works seamlessly on all devices
- **Interactive Slideshow**: Auto-rotating featured articles with navigation controls
- **Article Modal System**: Full articles display in a clean modal overlay
- **Modern UI**: Built with Tailwind CSS for a professional look
- **Category Tags**: Color-coded labels for different topics
- **Reading Time Estimates**: Helps users gauge article length
- **Smooth Animations**: Hover effects and transitions for better UX

## Technologies Used

- HTML5
- CSS3 (with Tailwind CSS framework)
- JavaScript (vanilla JS for all interactivity)
- Google Fonts (Inter font family)

## Installation

No installation required - this is a static website. Simply open the `blog.html` file in any modern web browser.

## How to Use

1. Browse featured articles in the slideshow at the top
2. Click "Read Full Article" or any article card to view content
3. Use the close button (×) to exit the article modal
4. Scroll down to view all available articles

## Customization

### Content Updates
1. Edit the `articles` object in the JavaScript section to modify existing articles
2. Add new articles by creating new entries in the `articles` object
3. Update the featured slideshow by adding new slide divs

### Styling Changes
1. Modify Tailwind classes throughout the HTML
2. Add custom CSS in the style tag if needed
3. Update color schemes by changing gradient and color classes

### Adding New Articles
1. Duplicate an existing article card in the "All Articles" section
2. Add a corresponding entry in the JavaScript `articles` object
3. Optionally, add a new slide to the featured articles slideshow

## Project Structure

```plaintext
blog.html
├── Header
├── Hero Section
├── Featured Articles Slideshow
├── All Articles Grid
│   ├── Article Cards (6 total)
│   └── Category tags & metadata
└── Footer
    ├── Site Info
    ├── Categories
    └── About Links
