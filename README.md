# Tantana - Coming Soon Page

A beautiful, modern "coming soon" splash screen with interactive features and animations.

## Features

- 🎨 **Modern Design**: Clean, glassmorphism-inspired design with gradient backgrounds
- ⏰ **Live Countdown Timer**: Dynamic countdown to launch date
- 📧 **Email Subscription**: Newsletter signup with form validation
- 📱 **Responsive Design**: Fully responsive across all devices
- ✨ **Smooth Animations**: Floating shapes, hover effects, and transitions
- 🎯 **Interactive Elements**: Social media links with ripple effects
- 🔔 **Notifications**: Toast notifications for user feedback

## Technologies Used

- HTML5
- CSS3 (with modern features like backdrop-filter, gradients)
- Vanilla JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Inter)

## Getting Started

1. **Clone or download** the project files
2. **Open** `index.html` in your web browser
3. **Customize** the content, colors, and launch date as needed

## Customization

### Changing the Launch Date
Edit the `launchDate` variable in `script.js`:
```javascript
const launchDate = new Date();
launchDate.setDate(launchDate.getDate() + 30); // Change 30 to your desired days
```

### Updating Colors
Modify the gradient colors in `styles.css`:
```css
body {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

### Adding Social Media Links
Update the social media links in `index.html`:
```html
<div class="social-links">
    <a href="https://twitter.com/yourhandle" class="social-link">
        <i class="fab fa-twitter"></i>
    </a>
    <!-- Add more social links -->
</div>
```

## File Structure

```
tantana-soon/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

Feel free to submit issues and enhancement requests! 