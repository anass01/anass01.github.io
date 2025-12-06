# GitHub Pages Portfolio

A modern, minimalist, premium-style portfolio website built with vanilla HTML, CSS, and JavaScript.

## Features

- Modern minimalist design with premium aesthetics
- Fully responsive layout (mobile-first approach)
- Smooth scrolling navigation
- Clean typography and ample white space
- Subtle animations and hover effects
- No external dependencies

## GitHub Pages Deployment

This repository is configured to work with GitHub Pages automatically. Follow these steps to deploy:

### Option 1: Automatic Deployment (Recommended)

1. Push your code to the `main` branch (or your default branch)
2. Go to your repository on GitHub
3. Navigate to **Settings** → **Pages**
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** (or your default branch) and **/ (root)**
6. Click **Save**
7. Your site will be available at `https://[username].github.io/[repository-name]`

### Option 2: Using GitHub Actions (Optional)

If you want more control over the deployment process, you can set up GitHub Actions workflows.

## Local Development

To view the portfolio locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/[username]/[repository-name].git
   cd [repository-name]
   ```

2. Open `index.html` in your web browser, or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

3. Navigate to `http://localhost:8000` in your browser

## File Structure

```
.
├── index.html      # Main HTML file
├── styles.css      # Stylesheet with modern minimalist design
├── script.js       # JavaScript for interactions and smooth scrolling
├── README.md       # This file
└── .gitignore     # Git ignore file
```

## Customization

To customize the portfolio:

1. **Colors**: Edit the CSS variables in `styles.css` under `:root`
2. **Content**: Update the text in `index.html`
3. **Styling**: Modify `styles.css` to match your preferences
4. **Interactions**: Adjust `script.js` for different behaviors

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available for personal and commercial use.

