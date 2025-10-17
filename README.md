# Paradise Salon Website

A modern, responsive single-page website for Paradise Salon featuring services, customer reviews, and Google Maps integration.

## Features

- Responsive design for all devices
- Smooth scrolling navigation
- Services showcase
- Customer reviews section
- Google Maps integration
- Contact form with validation
- Modern animations and transitions

## Setup

1. Open `index.html` in a web browser to view the site
2. To enable Google Maps, replace `YOUR_GOOGLE_MAPS_API_KEY` in `index.html` with your actual Google Maps API key
3. Update the salon coordinates in `script.js` (line 82) to match your actual location

## Getting Your Google Maps API Key

1. Go to [Google Cloud Console](https://console.cloud.google.com/)
2. Create a new project or select existing one
3. Enable Maps JavaScript API
4. Create credentials (API Key)
5. Replace `YOUR_GOOGLE_MAPS_API_KEY` in the HTML file

## Customization

- **Colors**: Edit CSS variables in `styles.css` (lines 9-15)
- **Content**: Update text in `index.html`
- **Location**: Change coordinates in `script.js` (line 82)
- **Services**: Modify service cards in the HTML
- **Reviews**: Update review cards with actual customer testimonials

## File Structure

```
paradise_ws/
├── index.html          # Main HTML file
├── styles.css          # Styling and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Local Development

For best results, use a local server:
- Python: `python -m http.server 8000`
- Node.js: `npx serve .`
- PHP: `php -S localhost:8000`

