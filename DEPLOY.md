# Deployment Guide - GitHub Pages

## Quick Start

### 1. Create GitHub Repository

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it `portfolio` or `ikram-portfolio`
3. Make it public (required for free GitHub Pages)
4. Don't initialize with README (we already have one)

### 2. Push Your Code

Run these commands in your terminal:

```bash
cd "/Users/mac/Documents/NODE JS/Portfolio"

# Add all files
git add .

# Commit
git commit -m "Initial commit: Portfolio website"

# Rename branch to main
git branch -M main

# Add remote (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/portfolio.git

# Push to GitHub
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll down to **Pages** section (left sidebar)
4. Under **Source**, select **GitHub Actions**
5. The workflow will automatically deploy your portfolio

### 4. Access Your Portfolio

Your portfolio will be live at:
```
https://YOUR_USERNAME.github.io/portfolio/
```

## Important Notes

### Contact Form
Since GitHub Pages only hosts static files, the contact form backend won't work. You have two options:

**Option 1: Use EmailJS (Recommended)**
- Sign up at [EmailJS](https://www.emailjs.com/)
- Update the contact form to use EmailJS instead of the backend API
- Free tier available

**Option 2: Deploy Backend Separately**
- Deploy the Node.js server to:
  - [Vercel](https://vercel.com) - Free
  - [Netlify](https://netlify.com) - Free
  - [Railway](https://railway.app) - Free tier
- Update the API endpoint in `script.js`

### Future Updates

To update your portfolio:
```bash
git add .
git commit -m "Update portfolio"
git push
```

GitHub Actions will automatically redeploy your site.

## Troubleshooting

- **404 Error**: Make sure GitHub Pages is enabled and source is set to "GitHub Actions"
- **Contact Form Not Working**: See "Contact Form" section above
- **Images Not Loading**: Check that all image paths are relative (e.g., `profile.png` not `/profile.png`)
