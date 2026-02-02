# Be My Valentine? 💕

An interactive Valentine's Day web page with playful animations, accessibility features, and a fun surprise!

## Features

- **Interactive Experience**: An evasive "No" button that moves around and eventually yields to "Yes"
- **Canvas Confetti**: Beautiful celebration animation when "Yes" is clicked
- **Emoji Icons**: Lovely emoji decorations instead of icon fonts
- **Floating Decorations**: Animated hearts and roses floating in the background
- **Keyboard Accessible**: Full keyboard support with Enter/Space for button activation
- **ARIA Attributes**: Proper semantic HTML and ARIA roles for screen reader accessibility
- **Visible Focus Styles**: Clear focus indicators for keyboard navigation
- **Responsive Design**: Works beautifully on mobile, tablet, and desktop devices

## Local Preview

To preview this page locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/isaiahlovett02-pixel/formylove2.0.git
   cd formylove2.0
   ```

2. Open `index.html` in your web browser:
   - **Double-click** the `index.html` file, or
   - **Right-click** and select "Open with" → Your preferred browser, or
   - Use a local development server:
     ```bash
     # Using Python 3
     python -m http.server 8000
     
     # Using Python 2
     python -m SimpleHTTPServer 8000
     
     # Using Node.js (if you have http-server installed)
     npx http-server
     ```

3. If using a development server, open your browser to `http://localhost:8000`

## GitHub Pages Deployment

This repository is configured to automatically deploy to GitHub Pages:

- **Automatic Deployment**: Every push to the `main` branch triggers a deployment
- **Manual Deployment**: Can also be triggered manually via GitHub Actions workflow
- **Live URL**: Once deployed, the page will be available at `https://isaiahlovett02-pixel.github.io/formylove2.0/`

### Setup GitHub Pages

1. Go to your repository **Settings** → **Pages**
2. Under "Source", select the `gh-pages` branch
3. Click **Save**
4. The workflow will automatically deploy the site on the next push to `main`

### Manual Deployment

To manually trigger a deployment:

1. Go to the **Actions** tab in your repository
2. Select the "Deploy to GitHub Pages" workflow
3. Click **Run workflow** → **Run workflow**

## How It Works

1. **Floating Decorations**: DOM elements are dynamically created and animated using CSS
2. **Evasive Button**: The "No" button repositions itself on hover and click, making it playfully hard to select
3. **Progressive Resistance**: After multiple "No" clicks, the button eventually accepts defeat and becomes a "Yes"
4. **Canvas Confetti**: Efficient particle system using HTML5 Canvas for smooth animations
5. **Accessibility**: Full keyboard support, ARIA labels, and screen reader announcements

## Browser Compatibility

- Chrome/Edge: ✅ Full support
- Firefox: ✅ Full support
- Safari: ✅ Full support
- Mobile browsers: ✅ Full support

## Technical Details

- Pure HTML, CSS, and vanilla JavaScript (no dependencies)
- Lightweight and fast-loading
- Accessible and semantic HTML
- Responsive CSS Grid and Flexbox layouts
- Modern JavaScript features (ES6+)

## License

Made with ❤️ for someone special

---

**Note**: This is a fun, interactive Valentine's Day page. Feel free to customize the messages and styling to make it your own!
