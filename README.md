# Portfolio Website - Deployment Instructions

This is your professional portfolio website built with HTML, CSS, and JavaScript. It's designed to be hosted on GitHub Pages.

## 🚀 Quick Start - Deploy to GitHub Pages

### Option 1: Using Your Existing GitHub.io Repository

If you already have a repository named `anu7699.github.io`:

1. Clone your repository:
   ```bash
   git clone https://github.com/anu7699/anu7699.github.io.git
   cd anu7699.github.io
   ```

2. Copy the `index.html` file to the root of your repository

3. Commit and push:
   ```bash
   git add index.html
   git commit -m "Add portfolio website"
   git push origin main
   ```

4. Your site will be live at: `https://anu7699.github.io`

### Option 2: Create a New GitHub.io Repository

If you don't have a GitHub.io repository yet:

1. Go to [GitHub](https://github.com) and create a new repository
2. Name it exactly: `anu7699.github.io` (replace with your GitHub username)
3. Make it public
4. Don't initialize with README

5. Then run:
   ```bash
   git init
   git add index.html README.md
   git commit -m "Initial commit - Portfolio website"
   git branch -M main
   git remote add origin https://github.com/anu7699/anu7699.github.io.git
   git push -u origin main
   ```

6. Your site will be live at: `https://anu7699.github.io` within a few minutes

### Option 3: Deploy to a Project Repository

If you want to keep this as a separate project:

1. Create a new repository on GitHub (e.g., `portfolio`)
2. Clone and add the files:
   ```bash
   git clone https://github.com/anu7699/portfolio.git
   cd portfolio
   # Copy index.html here
   git add .
   git commit -m "Add portfolio website"
   git push origin main
   ```

3. Enable GitHub Pages:
   - Go to repository Settings
   - Click "Pages" in the left sidebar
   - Under "Source", select "main" branch
   - Click Save

4. Your site will be live at: `https://anu7699.github.io/portfolio`

## 🎨 Customization

The website is fully self-contained in a single HTML file. You can customize:

### Colors
Edit the CSS variables at the top of the `<style>` section:
```css
:root {
    --primary: #0a0e27;      /* Main background */
    --accent: #00d4ff;       /* Accent color (cyan) */
    --accent-warm: #ff6b9d;  /* Secondary accent (pink) */
    /* ... */
}
```

### Content
All content is in the HTML. Simply find the section you want to edit and update the text.

### Links
Update your social links at the bottom:
- LinkedIn: Find `https://linkedin.com/in/anuagarwal7`
- GitHub: Find `https://github.com/anu7699`
- Email: Already set to `anua2@illinois.edu`

## 📱 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile
- **Smooth Animations**: Scroll-based animations and hover effects
- **Modern UI**: Clean, professional design with a dark theme
- **Fast Loading**: Single HTML file, no dependencies
- **SEO Optimized**: Proper semantic HTML structure

## 🛠 Local Testing

To test locally before deploying:

1. Simply open `index.html` in your browser
2. Or use a local server:
   ```bash
   # Python 3
   python -m http.server 8000
   
   # Then visit http://localhost:8000
   ```

## 📄 File Structure

```
portfolio/
├── index.html          # Your complete website
└── README.md          # This file
```

## 💡 Tips

1. **Custom Domain**: You can add a custom domain in GitHub Pages settings
2. **Analytics**: Add Google Analytics by inserting the tracking code before `</head>`
3. **Updates**: Just edit `index.html` and push - changes go live automatically
4. **Backup**: Keep the original HTML file as a backup before making changes

## 🎯 What's Included

- Hero section with your introduction
- Experience timeline with all positions
- Publications with proper citations
- Featured projects
- Education credentials with GPA
- Technical skills organized by category
- Professional footer with social links

## 📞 Need Help?

If you encounter any issues:
1. Check the GitHub Pages documentation: https://pages.github.com
2. Verify the repository name is correct (`username.github.io`)
3. Make sure the repository is public
4. Wait 5-10 minutes after pushing for changes to appear

---

Built with ❤️ using modern web technologies
