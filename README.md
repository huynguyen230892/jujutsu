# Jujutsu Landing Page

A modern, responsive landing page for the Jujutsu comic reader iOS application.

## Features

- Fully static HTML/CSS/JavaScript
- Responsive design (mobile, tablet, desktop)
- Smooth animations and transitions
- Mobile-friendly navigation
- FAQ accordion
- Ready for GitHub Pages hosting

## Deployment to GitHub Pages

### Option 1: Deploy from repository root

1. Push all files to your GitHub repository
2. Go to repository Settings → Pages
3. Under "Source", select the branch (usually `main` or `master`)
4. Select `/ (root)` as the folder
5. Click Save
6. Your site will be available at `https://yourusername.github.io/repository-name/`

### Option 2: Deploy from docs folder

1. Create a `docs` folder in your repository
2. Move all files (`index.html`, `styles.css`, `script.js`) into the `docs` folder
3. Go to repository Settings → Pages
4. Under "Source", select the branch
5. Select `/docs` as the folder
6. Click Save

## Local Development

Simply open `index.html` in your web browser, or use a local server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## Customization

- **App Name**: Search and replace "Jujutsu" throughout the files
- **Colors**: Edit CSS variables in `styles.css` (lines 6-13)
- **Content**: Modify text in `index.html`
- **App Store Link**: Update the download button links with your App Store URL

## File Structure

```
jujutsu-landing/
├── index.html      # Main HTML file
├── styles.css      # All styles and responsive design
├── script.js       # Interactive functionality
└── README.md       # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## License

All rights reserved.

