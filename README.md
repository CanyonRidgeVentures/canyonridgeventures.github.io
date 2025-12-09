# Big Bridge Ventures Website

A simple, modern static website for Big Bridge Ventures - a real estate investing company focused on affordable homeownership, AI-powered innovation, and diverse portfolio management.

## Features

- **Responsive Design**: Works beautifully on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Custom Graphics**: SVG illustrations featuring houses, people, and key exchanges
- **GitHub Pages Ready**: Simple setup for hosting on GitHub Pages

## Corporate Goals

1. **Affordable Homeownership**: Creating opportunities for everyone to have an affordable home
2. **AI-Powered Innovation**: Leveraging AI for useful and productive uses in real estate investing
3. **Diverse Portfolio**: Maintaining a diverse and varied portfolio for stability

## Setup for GitHub Pages

### Option 1: Quick Setup (Recommended)

1. Create a new repository on GitHub (e.g., `big-bridge-ventures-website`)
2. Upload all files from this directory to the repository
3. Go to your repository settings
4. Navigate to "Pages" in the left sidebar
5. Under "Source", select "Deploy from a branch"
6. Choose "main" (or "master") branch and "/ (root)" folder
7. Click "Save"
8. Your site will be available at `https://[your-username].github.io/[repository-name]`

### Option 2: Using GitHub CLI

```bash
# Initialize git repository (if not already done)
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Big Bridge Ventures website"

# Add remote repository (replace with your repository URL)
git remote add origin https://github.com/[your-username]/[repository-name].git

# Push to GitHub
git push -u origin main

# Then follow steps 4-8 from Option 1 to enable GitHub Pages
```

### Option 3: Custom Domain (Optional)

If you have a custom domain:

1. Add a `CNAME` file in the root directory with your domain name
2. Configure DNS settings with your domain provider to point to GitHub Pages
3. Update the CNAME file in GitHub repository settings

## File Structure

```
.
├── index.html          # Main HTML file
├── styles.css          # CSS styling
└── README.md          # This file
```

## Local Development

To preview the website locally:

1. Simply open `index.html` in your web browser, or
2. Use a local server (recommended):

```bash
# Using Python 3
python3 -m http.server 8000

# Using Python 2
python -m SimpleHTTPServer 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Then visit http://localhost:8000 in your browser
```

## Customization

### Updating Contact Information

Edit the contact section in `index.html` (around line 200) to update email and phone number.

### Changing Colors

Modify the color scheme in `styles.css`. The main brand color is `#4a90e2` (blue).

### Adding Content

The website is structured with clear sections. Simply edit the HTML content in `index.html` to add or modify text.

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

© 2024 Big Bridge Ventures. All rights reserved.

