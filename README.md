# Houston Spartans Website Template

A modern, responsive HTML/CSS/JavaScript template inspired by the Houston Spartans esports organization website. This template features a sleek dark theme with orange accents, smooth animations, and mobile-responsive design.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Dark theme with vibrant orange gradient accents
- **Smooth Animations**: CSS animations and JavaScript interactions
- **Interactive Elements**: Contact form, navigation, and hover effects
- **Modular Structure**: Well-organized HTML, CSS, and JavaScript files
- **Accessibility**: Semantic HTML and proper contrast ratios

## Sections Included

1. **Navigation Bar**: Fixed header with smooth scrolling links
2. **Hero Section**: Welcome banner with call-to-action
3. **Mission Section**: Three-card layout for Competition, Community, and Content
4. **Partners Section**: Logo grid for sponsors/partners
5. **Community Section**: Three-step process with numbered cards
6. **Our Spartans**: Team member profiles with social links
7. **Play & Shop**: Dual-section layout for gaming and merchandise
8. **News Section**: Blog-style cards for latest updates
9. **Contact Section**: Contact form with validation and info
10. **Footer**: Links and social media icons

## File Structure

```
houston-spartans-clone/
├── index.html          # Main HTML file
├── styles.css          # All CSS styles and responsive design
├── script.js           # JavaScript functionality and interactions
└── README.md           # This file
```

## Getting Started

1. **Clone or Download**: Get the template files
2. **Open in Browser**: Simply open `index.html` in your web browser
3. **Customize**: Edit the content, colors, and images to match your needs

## Customization Guide

### Colors
The main color scheme uses:
- **Primary Orange**: `#ff6b35`
- **Secondary Orange**: `#f7931e`
- **Dark Background**: `#0a0a0a`
- **Secondary Dark**: `#111111`
- **Text Light**: `#ffffff`
- **Text Secondary**: `#cccccc`

To change colors, update the CSS variables or search and replace the hex values in `styles.css`.

### Images
Replace placeholder images with your own:
- Logo: Update the navbar logo
- Hero video placeholder: Add your video or image
- Partner logos: Replace with actual partner/sponsor logos
- Team member photos: Update spartan profile images
- News thumbnails: Add actual blog post images

### Content
- Edit text content directly in `index.html`
- Update social media links in the footer and team sections
- Modify contact information in the contact section
- Add or remove team members by duplicating the spartan card structure

### Adding New Sections
1. Add HTML structure in `index.html`
2. Add corresponding styles in `styles.css`
3. Add any JavaScript functionality in `script.js`
4. Update navigation links if needed

## JavaScript Features

- **Mobile Navigation**: Hamburger menu with smooth toggle
- **Smooth Scrolling**: Navigation links scroll to sections
- **Form Validation**: Contact form with email validation
- **Notifications**: Toast-style messages for user feedback
- **Scroll Animations**: Elements fade in as they come into view
- **Interactive Effects**: Hover animations and click effects

## Browser Support

- Chrome/Chromium 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Performance Tips

1. **Image Optimization**: Compress images for web use
2. **Font Loading**: Consider using font-display: swap for web fonts
3. **Minification**: Minify CSS and JavaScript for production
4. **CDN**: Use CDN for Font Awesome icons in production

## Accessibility Features

- Semantic HTML structure
- Proper heading hierarchy
- Alt text for images (add your own descriptions)
- Keyboard navigation support
- Color contrast compliance
- Screen reader friendly

## Mobile Optimization

- Responsive grid layouts
- Touch-friendly button sizes
- Optimized font sizes for mobile
- Hamburger navigation menu
- Swipe-friendly card layouts

## Deployment

### GitHub Pages
1. Push files to a GitHub repository
2. Enable GitHub Pages in repository settings
3. Your site will be available at `username.github.io/repository-name`

### Netlify
1. Drag and drop the folder to Netlify
2. Your site will be deployed instantly with a custom URL

### Traditional Web Hosting
1. Upload all files to your web server
2. Ensure `index.html` is in the root directory

## Customization Examples

### Changing the Color Scheme
```css
/* In styles.css, replace orange colors with your brand colors */
:root {
    --primary-color: #your-color;
    --secondary-color: #your-secondary-color;
}
```

### Adding a New Team Member
```html
<!-- In index.html, duplicate this structure in the spartans-grid -->
<div class="spartan-card">
    <div class="spartan-image">
        <img src="path-to-image.jpg" alt="Member Name">
    </div>
    <div class="spartan-info">
        <h3>MEMBER NAME</h3>
        <p>ROLE/TITLE</p>
        <span class="role">POSITION</span>
        <div class="social-links">
            <a href="#"><i class="fab fa-twitter"></i></a>
            <a href="#"><i class="fab fa-instagram"></i></a>
        </div>
    </div>
</div>
```

### Adding Analytics
Add your analytics code before the closing `</head>` tag in `index.html`.

## License

This template is provided as-is for educational and personal use. The original Houston Spartans branding and content belong to their respective owners.

## Credits

- **Font Awesome**: Icons
- **Google Fonts**: Inter font family
- **Inspiration**: Houston Spartans official website

## Support

For questions or issues with this template, please refer to the code comments or create an issue in the repository.

---

**Note**: This is a template recreation for educational purposes. Replace all placeholder content with your own before using in production.
# houston-spartans-landing
