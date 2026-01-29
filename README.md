# Ikram Ullah - Portfolio Website

A modern, responsive portfolio website showcasing the work and expertise of Ikram Ullah, Fullstack Developer (Professional in Flutter).

## Features

- **Dark Theme Design**: Modern dark theme with orange accents matching professional portfolio standards
- **Responsive Layout**: Fully responsive design that works on all devices
- **Sticky Sidebar**: Fixed sidebar with profile information and social links
- **Smooth Animations**: Scroll-triggered animations and transitions
- **Contact Form**: Functional contact form with email integration
- **Project Showcase**: Display of live projects and work experience
- **Skills Visualization**: Interactive skill bars with percentages

## Tech Stack

- **Backend**: Node.js with Express.js
- **Frontend**: HTML5, CSS3, JavaScript (Vanilla)
- **Email**: Nodemailer for contact form submissions
- **Styling**: Custom CSS with CSS Variables

## Installation

1. Clone or download this repository
2. Install dependencies:
```bash
npm install
```

3. Create a `.env` file in the root directory (optional, for email functionality):
```
PORT=3000
SMTP_HOST=smtp.gmail.com
SMTP_PORT=587
SMTP_USER=your-email@gmail.com
SMTP_PASS=your-app-password
```

## Running the Application

### Development Mode
```bash
npm run dev
```

### Production Mode
```bash
npm start
```

The application will be available at `http://localhost:3000`

## Project Structure

```
Portfolio/
├── public/
│   ├── index.html      # Main HTML file
│   ├── styles.css      # All styling
│   └── script.js       # JavaScript functionality
├── server.js           # Express server
├── package.json        # Dependencies
└── README.md          # This file
```

## Sections

1. **Hero Section**: Introduction and call-to-action
2. **My Journey & Vision**: Personal story and philosophy
3. **Experience**: Work history and roles
4. **Services**: Offered services and solutions
5. **Skills**: Technical skills with visual indicators
6. **Projects**: Portfolio of live projects
7. **Testimonials**: Client feedback
8. **Contact**: Contact form and information

## Customization

### Update Profile Information
Edit the sidebar section in `public/index.html`:
- Profile image (update the `src` attribute)
- Name and title
- Social media links
- Email address

### Update Projects
Modify the projects section in `public/index.html` to add or update your projects.

### Update Skills
Edit the skills grid in `public/index.html` and adjust percentages in `styles.css`.

### Color Scheme
Modify CSS variables in `public/styles.css`:
```css
:root {
    --primary-color: #FF6B35;  /* Orange accent color */
    --bg-dark: #0a0a0a;        /* Dark background */
    --text-primary: #ffffff;    /* Primary text color */
}
```

## Email Configuration

To enable the contact form email functionality:

1. Set up SMTP credentials in your `.env` file
2. For Gmail, you'll need to:
   - Enable 2-factor authentication
   - Generate an App Password
   - Use the App Password in `SMTP_PASS`

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Deployment to GitHub Pages

This portfolio can be deployed to GitHub Pages for free hosting.

### Steps to Deploy:

1. **Create a GitHub Repository:**
   ```bash
   # Create a new repository on GitHub (e.g., "portfolio" or "ikram-portfolio")
   ```

2. **Push to GitHub:**
   ```bash
   git add .
   git commit -m "Initial commit: Portfolio website"
   git branch -M main
   git remote add origin https://github.com/ikramakro/portfolio.git
   git push -u origin main
   ```

3. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click on "Settings" → "Pages"
   - Under "Source", select "GitHub Actions"
   - The workflow will automatically deploy your portfolio

4. **Your portfolio will be live at:**
   ```
   https://ikramakro.github.io/portfolio/
   ```

### Note:
- The contact form requires a backend server. For GitHub Pages (static hosting), you can:
  - Use a service like Formspree, EmailJS, or Netlify Forms
  - Or deploy the full Node.js app to services like Vercel, Netlify, or Railway

## License

MIT License - feel free to use this portfolio template for your own projects.

## Contact

**Ikram Ullah**
- Email: ikramullahakro@gmail.com
- Phone: +92 334 5959021
- LinkedIn: [LinkedIn Profile](https://www.linkedin.com/in/ikram-ullah-004489214/)
- GitHub: [GitHub Profile](https://github.com/ikramakro)
- Stack Overflow: [Stack Overflow Profile](https://stackoverflow.com/users/14614664/ikram-ullah)

---

Built with ❤️ by Ikram Ullah
