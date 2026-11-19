# Clinical Psychology Website Template

A modern, responsive website template designed for clinical psychologists and therapists to showcase their services and enable online appointment booking.

## Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Service Showcase** - Dedicated sections for different therapy types
- **Online Appointment Form** - Integrated contact/booking form
- **SEO Optimized** - Semantic HTML, meta tags, and structured data (Schema.org)
- **Accessibility** - WCAG 2.1 compliant with proper ARIA labels
- **Performance** - Optimized assets and lazy loading

## Tech Stack

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **Vanilla JavaScript** - Lightweight interactions and animations
- **FormSubmit** - Serverless form handling (no backend required)

## Project Structure

```
├── index.html          # Main HTML file
└── README.md           # This file
```

## Getting Started

### Prerequisites

- A modern web browser
- A code editor (VS Code recommended)
- Optional: Local development server (Live Server extension for VS Code)

### Installation

1. Clone or download this repository
2. Open `index.html` in your browser
3. For development, use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (npx)
   npx serve
   
   # Using PHP
   php -S localhost:8000
   ```

## Customization

### Content Updates

Edit the following sections in `index.html`:

- **Hero Section** - Update headline, subheadline, and CTA buttons
- **About Section** - Modify professional background and credentials
- **Services** - Add/remove therapy types and descriptions
- **Contact Form** - Update form fields and FormSubmit endpoint
- **Footer** - Update contact information and social links

### Styling

The project uses Tailwind CSS via CDN. To customize:

1. Modify the Tailwind config in the `<head>` section
2. Update CSS custom properties for colors, spacing, etc.
3. Add custom styles in the `<style>` block

### Form Handling

The contact form uses [FormSubmit](https://formsubmit.co/) for serverless form processing:

1. Create a FormSubmit account
2. Update the form `action` URL with your endpoint
3. Replace the `access_key` hidden input with your key
4. Configure email notifications in FormSubmit dashboard

## SEO Configuration

Update the following meta tags in `<head>`:

- `title` - Page title
- `meta name="description"` - Page description (150-160 chars)
- `meta name="keywords"` - Relevant keywords
- Open Graph tags (`og:title`, `og:description`, `og:image`)
- Twitter Card tags
- JSON-LD structured data for LocalBusiness/MedicalBusiness

## Deployment

### Static Hosting Options

- **Netlify** - Drag & drop or connect to Git
- **Vercel** - Connect to Git repository
- **GitHub Pages** - Enable in repository settings
- **Cloudflare Pages** - Connect to Git
- **Firebase Hosting** - `firebase deploy`

### Custom Domain

1. Purchase a domain from a registrar
2. Configure DNS records (A record + CNAME for www)
3. Add domain in hosting provider dashboard
4. Enable HTTPS/SSL

## Performance Optimization

- Enable compression (gzip/brotli) on server
- Leverage browser caching
- Use a CDN for static assets
- Optimize images (WebP format, appropriate dimensions)
- Minify HTML/CSS/JS for production

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome for Android)

## Accessibility

This template follows WCAG 2.1 AA guidelines:

- Semantic HTML structure
- Proper heading hierarchy (h1-h6)
- Alt text for all images
- Focus indicators for interactive elements
- Color contrast ratios (4.5:1 minimum)
- Keyboard navigation support
- Screen reader compatible

## License

This project is open source and available under the [MIT License](LICENSE).

## Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request


**Note:** This is a template. Replace all placeholder content with your actual information before deploying to production.
