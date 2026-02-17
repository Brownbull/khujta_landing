# khujta ai - Strategic AI Solutions Website

A professional static marketing website for khujta ai, showcasing AI agent development services, expert agents, and AI applications.

## Overview

khujta ai is an AI development agency specializing in:
- Custom AI agents for legal, tax, and business domains
- Agent development services (PMAT Suite, Claude Code, custom frameworks)
- Production AI applications
- Development methodologies: Ralph Loop, GSD, ECC

**Important**: We provide strategic guidance, NOT licensed professional services (legal, tax, etc.).

## Live Site

The website is deployed at: https://brownbull.github.io/khujta_landing/

## Project Structure

```
khujta-ai-agency-website/
├── index.html          # Main homepage
├── css/
│   └── styles.css      # Main stylesheet
├── js/                 # JavaScript files (for future use)
├── images/             # Images (for future use)
├── pages/              # Additional pages (for future use)
├── mockups/           # Design mockups for different personas
├── robots.txt          # Search engine robots config
└── .nojekyll          # GitHub Pages configuration
```

## Development

### Prerequisites
- Any modern web browser
- Text editor (VS Code recommended)

### Running Locally
1. Clone the repository
2. Open `index.html` in your browser
3. Or use a local server:
   ```bash
   npx serve .
   # or
   python -m http.server 8000
   ```

### Customization

#### Colors and Theme
Edit CSS variables in `css/styles.css`:
```css
:root {
    --primary: #0f172a;
    --secondary: #1e40af;
    --accent: #3b82f6;
    /* ... more variables */
}
```

#### Content Updates
- Edit sections directly in `index.html`
- Each section is marked with HTML comments (e.g., `<!-- Services Section -->`)

## Deployment

### GitHub Pages

1. Push to GitHub repository
2. Go to Repository Settings > Pages
3. Select source: "Deploy from a branch"
4. Choose branch: `main` (or `gh-pages`)
5. Folder: `/ (root)`
6. Click Save

The site will be available at: `https://yourusername.github.io/repo-name/`

### Custom Domain
1. Add `CNAME` file with your domain
2. Configure your domain's DNS to point to GitHub Pages

## SEO

The website includes:
- Meta description
- Open Graph tags for social sharing
- Semantic HTML structure
-robots.txt for search engines

## Contact

- Email: khujta.ai@gmail.com
- For issues/suggestions: Open a GitHub issue

## Design Mockups

The `mockups/` directory contains 5 persona-specific designs:
- `enterprise.html` - Enterprise tech companies
- `professional-services.html` - Legal/Professional services
- `healthcare.html` - Healthcare organizations
- `startup.html` - Small businesses/Startups
- `government.html` - Government/Defense contractors

## Technologies

- Pure HTML5, CSS3, JavaScript
- No build tools required
- CSS Grid and Flexbox for responsive design
- CSS custom properties for theming

## License

Private - All rights reserved.
