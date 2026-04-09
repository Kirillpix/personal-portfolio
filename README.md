# Anton Sarychev - AI/LLM Developer Portfolio

A modern, professional single-page portfolio website built with Tailwind CSS.

## 🚀 Quick Deploy to GitHub Pages (30 seconds)

### Option 1: Using GitHub UI (Easiest)

1. **Create a new repository** on GitHub (e.g., `anton-portfolio`)
2. **Upload files**: Upload `index.html` to the repository
3. **Go to Settings** → **Pages**
4. **Source**: Select `Deploy from a branch`
5. **Branch**: Select `main` (or `master`) and `/ (root)`
6. Click **Save**
7. **Done!** Your site will be live at `https://yourusername.github.io/anton-portfolio/`

### Option 2: Using Git Command Line

```bash
# Clone your new repository
git clone https://github.com/yourusername/anton-portfolio.git
cd anton-portfolio

# Copy the index.html file (already done if you're in this repo)

# Commit and push
git add .
git commit -m "Initial commit: Portfolio website"
git push origin main

# Enable GitHub Pages:
# Go to Settings → Pages → Select "main" branch → Save
```

## 📁 Project Structure

```
anton-portfolio/
├── index.html          # Main HTML file (all-in-one)
└── README.md           # This file
```

## ✨ Features

- **Modern Dark Theme** with neon/cyber-AI accents (blues, purples, cyans)
- **Fully Responsive** - Mobile-first design
- **Smooth Animations** - Intersection Observer for fade-in effects
- **SEO Optimized** - Proper meta tags and Open Graph
- **Tailwind CSS via CDN** - No build process required
- **Zero Configuration** - Deploy anywhere instantly

## 🎨 Customization

### Update Contact Information

Edit `index.html` and search for:
- `anton.sarychev@example.com` - Replace with your email
- `@yourusername` - Replace with your Telegram username
- `https://github.com/yourusername` - Replace with your GitHub profile
- `https://linkedin.com/in/yourusername` - Replace with your LinkedIn

### Add Your CV

1. Add your PDF file (e.g., `cv.pdf`) to the repository
2. In `index.html`, find all instances of `href="#"` for "Download CV"
3. Replace with `href="cv.pdf"` or `href="./assets/cv.pdf"`

### Change Colors

In the `<script>` tag configuring Tailwind, modify the color values:
```javascript
colors: {
    'neon-blue': '#00f3ff',      // Change these
    'neon-purple': '#bc13fe',    // to your preferred
    'neon-cyan': '#0affc2',      // colors
}
```

## 🌐 Local Development Preview

### Option 1: Python Simple HTTP Server

```bash
# Navigate to the project directory
cd /path/to/anton-portfolio

# Start server
python -m http.server 8000

# Open browser to http://localhost:8000
```

### Option 2: VS Code Live Server

1. Install "Live Server" extension in VS Code
2. Right-click `index.html`
3. Select "Open with Live Server"

### Option 3: Direct File Open

Simply open `index.html` in any modern browser (some features may be limited without a server).

## 📱 Sections

1. **Navbar** - Sticky navigation with mobile menu
2. **Hero** - Introduction with animated background
3. **About** - Professional summary and core expertise
4. **Skills** - Grid layout with categorized technologies
5. **Experience** - Timeline of work history
6. **Projects** - Featured projects with special highlight
7. **Education & Hackathons** - Academic background and achievements
8. **Contact** - Contact information and social links
9. **Footer** - Copyright and quick links

## 🔧 Technologies Used

- **HTML5** - Semantic markup
- **Tailwind CSS (CDN)** - Utility-first CSS framework
- **Font Awesome** - Icon library
- **Google Fonts** - Inter and JetBrains Mono fonts
- **Vanilla JavaScript** - No frameworks, pure JS for interactions

## 📊 Performance

- **Lightweight**: Single HTML file, no build process
- **Fast Loading**: CDN resources, minimal custom CSS
- **Accessible**: Semantic HTML, proper ARIA labels
- **SEO-Friendly**: Meta tags, Open Graph, structured content

## 🤝 Contributing

Feel free to fork this project and customize it for your own use!

## 📄 License

This project is open source and available under the MIT License.

---

**Built with ❤️ by Anton Sarychev**

*AI/LLM Developer | Python Engineer | Autonomous AI Agents*
