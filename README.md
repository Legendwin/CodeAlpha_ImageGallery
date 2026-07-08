# CodeAlpha ImageGallery

A modern, responsive image gallery application built with vanilla JavaScript and HTML5. Browse beautiful images from the Pexels API with an elegant user interface featuring dark/light theme support, search functionality, and a lightbox modal viewer.

## Features

- 🖼️ **Dynamic Image Loading** - Fetches high-quality images from the Pexels API
- 🔍 **Search Functionality** - Search and filter images by keywords
- 🌓 **Dark/Light Theme** - Toggle between light and dark modes with persistent storage
- 📱 **Responsive Design** - Adaptive masonry layout that works on all screen sizes
- 🖱️ **Lightbox Viewer** - Full-screen image viewer with navigation controls
- ⬆️ **Back to Top Button** - Quick navigation to the top of the page
- ♿ **Accessible** - ARIA labels and semantic HTML for better accessibility
- 📦 **Lightweight** - No external dependencies, pure vanilla JavaScript

## Project Structure

```
Image Gallery/
├── index.html      # Main HTML structure
├── style.css       # Styling and theme variables
└── script.js       # JavaScript functionality
```

## Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (for Pexels API access)

## Usage

### Features Explained

- **Search Images**: Type a keyword in the search box at the top to filter images
- **Toggle Theme**: Click the moon/sun icon in the navigation bar to switch between dark and light modes
- **View Full Size**: Click on any image to open it in the lightbox modal
- **Navigate in Lightbox**: Use arrow buttons or keyboard arrows to navigate through images
- **Load More**: Click the "More" button to load additional images
- **Back to Top**: Click the arrow button in the bottom-right corner to scroll to the top

### Keyboard Shortcuts

- **←/→ Arrow Keys**: Navigate between images in lightbox
- **ESC**: Close the lightbox modal

## Technical Details

### API Integration

The gallery uses the **Pexels API** for image content:
- Endpoint: `https://api.pexels.com/v1/`
- Authentication: API Key-based
- Rate Limit: 200 requests per hour for free tier

### Theme System

The application uses CSS custom properties (variables) for theming:

**Light Theme:**
- Background: Light gray (#f5f5f5)
- Cards: Darker gray (#e4e4e4)
- Text: Black (#000000)

**Dark Theme:**
- Background: Dark (#0b0c0e)
- Cards: Slightly lighter dark (#0f1113)
- Text: Green tint (#1B5E20)

### Responsive Breakpoints

- Desktop: 3-column layout
- Tablet: 2-column layout
- Mobile: 1-column layout (auto-adjusts based on screen width)

## Browser Compatibility

- Chrome/Chromium: ✅ Full support
- Firefox: ✅ Full support
- Safari: ✅ Full support (12+)
- Edge: ✅ Full support
- IE: ❌ Not supported (uses ES6+ features)

## Author

**Legendwin** - [GitHub Profile](https://github.com/Legendwin)

## Acknowledgments

- Images provided by [Pexels](https://www.pexels.com/) - A source of free stock photos
- Inspired by modern web design practices and accessibility standards