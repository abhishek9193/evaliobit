# EvalIOBit Incubator Website

A modern, minimalist website for EvalIOBit Incubator (OPC) Pvt Ltd, showcasing our IT services, product development, and digital content creation capabilities.

## Features

- Responsive design that works on all devices
- Modern, minimalist aesthetic
- Fast loading and optimized performance
- Smooth scrolling and animations
- Mobile-friendly navigation
- Contact form integration
- Social media integration

## Tech Stack

- HTML5
- CSS3 (with CSS Variables and Flexbox/Grid)
- Vanilla JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Inter)

## Project Structure

```
evaliobit-website/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── images/
├── assets/
└── README.md
```

## Deployment Options

### Option A: Netlify Deployment (Recommended)

1. Create a Netlify account at [netlify.com](https://netlify.com)
2. Install Netlify CLI (optional):
   ```bash
   npm install -g netlify-cli
   ```
3. Deploy using one of these methods:
   - Drag and drop the `evaliobit-website` folder to Netlify's dashboard
   - Use Netlify CLI:
     ```bash
     cd evaliobit-website
     netlify deploy
     ```
4. Configure your custom domain in Netlify's dashboard

### Option B: GitHub Pages Deployment

1. Create a new GitHub repository
2. Push your code to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin <your-repository-url>
   git push -u origin main
   ```
3. Go to repository Settings > Pages
4. Select the main branch as the source
5. Your site will be available at `https://<username>.github.io/<repository-name>`

### Option C: Traditional Hosting (cPanel)

1. Log in to your cPanel account
2. Navigate to File Manager
3. Upload the contents of the `evaliobit-website` folder to the `public_html` directory
4. Configure your domain in cPanel's DNS settings

## Customization

### Colors
The website uses CSS variables for easy color customization. Edit the following variables in `css/style.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --text-color: #1f2937;
    --light-text: #6b7280;
    --background: #ffffff;
    --light-background: #f3f4f6;
    --border-color: #e5e7eb;
}
```

### Content
- Update text content in `index.html`
- Add/remove services in the services section
- Update contact information
- Add social media links in the footer

### Images
- Place new images in the `images` directory
- Update image paths in `index.html`

## Maintenance

### Regular Updates
1. Keep content fresh and up-to-date
2. Monitor and update dependencies
3. Test across different devices and browsers
4. Check for broken links and forms

### Performance Optimization
1. Optimize images before uploading
2. Minify CSS and JavaScript files
3. Enable browser caching
4. Use a CDN for assets

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Android Chrome)

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is proprietary and confidential. All rights reserved. 