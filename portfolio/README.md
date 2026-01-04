# Sasidhar S - Cybersecurity Portfolio

A security-focused personal portfolio website for Sasidhar S, a Cybersecurity Student at SKCET. Built with pure HTML, CSS, and JavaScript.

## Features

- **Dark Terminal Theme**: Security operation center (SOC) inspired design
- **Security-First Content**: Focused on cybersecurity student perspective
- **Animated Background**: Canvas-based network visualization
- **Typing Animation**: Terminal-style text animation
- **Responsive Design**: Mobile-first, fully responsive
- **Form Validation**: Secure client-side form validation
- **Smooth Animations**: Scroll-triggered animations

## Tech Stack

- **HTML5**: Semantic markup
- **CSS3**: Modern CSS with custom properties
- **JavaScript (Vanilla)**: No frameworks or dependencies
- **Canvas API**: Background animation

## Getting Started

1. Clone or download this repository
2. Open `index.html` in your web browser
3. That's it! No build process, no dependencies

Alternatively, you can use a local development server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server
```

Then open `http://localhost:8000` in your browser.

## Customization

### Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --terminal-green: #00ff41;
    --terminal-blue: #00d9ff;
    --terminal-amber: #ffb020;
    --bg-dark: #0a0a0a;
    /* ... */
}
```

### Content

Update the content directly in `index.html`:
- Hero section: Main headline and subtitle
- About section: Personal story
- Skills section: Your skills and levels
- Projects section: Your projects
- Learning section: Your learning journey
- Contact section: Contact information and social links

### Typing Animation

Change the typing text in `script.js`:

```javascript
const fullText = 'Your custom text here.';
```

## File Structure

```
portfolio/
├── index.html      # Main HTML file
├── styles.css      # All styles
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Security Notes

- Form validation is client-side only (for demo purposes)
- In production, always validate on the server
- No external dependencies or CDN resources (except Google Fonts)
- All code is readable and auditable

## License

Feel free to use this portfolio template for your own projects!

## Credits

Fonts used:
- Inter (display font from Google Fonts)
- JetBrains Mono (monospace font from Google Fonts)

