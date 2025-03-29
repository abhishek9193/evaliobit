# EvalIOBit Website

This is the official website for EvalIOBit Incubator, showcasing our IT services, products, and digital innovation solutions.

## Features

- Modern, responsive design
- Mobile-friendly navigation
- Contact form with email integration
- Smooth scrolling
- Animated sections
- Portfolio showcase (coming soon)

## Technologies Used

- HTML5
- CSS3
- JavaScript (Vanilla)
- Font Awesome Icons
- Google Fonts (Poppins & Inter)

## Deployment on GitHub Pages

1. Create a new repository on GitHub
2. Push your code to the repository:
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/[your-username]/[repository-name].git
   git push -u origin main
   ```

3. Go to your repository's Settings
4. Scroll down to the "GitHub Pages" section
5. Under "Source", select the `main` branch
6. Click "Save"

Your site will be available at `https://[your-username].github.io/[repository-name]`

## Local Development

To run this website locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/[your-username]/[repository-name].git
   ```

2. Navigate to the project directory:
   ```bash
   cd [repository-name]
   ```

3. Open `index.html` in your web browser or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve
   ```

4. Visit `http://localhost:8000` in your browser

## Contact Form

The contact form uses a `mailto:` link to open the user's default email client. When a user submits the form:
1. Their email client will open
2. The form data will be pre-filled in the email
3. They can review and send the email

## Project Structure

```
evaliobit-website/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
└── README.md
```

## License

This project is proprietary and confidential. All rights reserved. 