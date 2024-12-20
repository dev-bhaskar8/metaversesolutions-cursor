# MetaverseSolutions Website

A modern, responsive website for MetaverseSolutions - a Web3 & Crypto Advisory firm.

## Deployment on Cloudflare Pages

### Prerequisites

1. A Cloudflare account
2. Git repository with your code (GitHub, GitLab, or Bitbucket)

### Deployment Steps

1. Log in to your Cloudflare dashboard
2. Go to Pages > Create a project > Connect to Git
3. Select your repository and configure as follows:

```bash
# Build settings
Build command: npm run build
Build output directory: /
Root directory: /
```

4. Environment variables (if needed):
   - None required for basic setup

5. Click "Save and Deploy"

### Custom Domain Setup

1. Go to your project's settings in Cloudflare Pages
2. Navigate to "Custom domains"
3. Click "Set up a custom domain"
4. Enter your domain (e.g., metaversesolutions.com)
5. Follow the DNS configuration instructions

### Deployment Features

- Automatic HTTPS
- Global CDN
- Automatic builds on git push
- Preview deployments for pull requests
- Custom domain support
- Zero configuration needed

## Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/metaversesolutions.git
cd metaversesolutions
```

2. Install dependencies:
```bash
npm install
```

3. Start local server:
```bash
npm start
```

## Project Structure

```
metaversesolutions/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── main.js            # JavaScript functionality
├── images/            # Image assets
│   ├── hero-bg.webp
│   ├── about-image.webp
│   ├── insight1.webp
│   └── insight2.webp
├── icons/             # Favicon and app icons
├── site.webmanifest   # PWA configuration
├── robots.txt         # Search engine configuration
└── sitemap.xml        # Site structure for SEO
```

## Features

- Responsive design
- Dark/Light mode
- Modern UI with animations
- SEO optimized
- Performance optimized
- PWA ready
- Contact form
- Newsletter subscription
- Lazy loading images

## Tech Stack

- HTML5
- CSS3 (with CSS Variables)
- JavaScript (ES6+)
- AOS (Animate On Scroll)
- Font Awesome Icons
- Google Fonts (Inter)

## Performance Optimization

- WebP image format
- Lazy loading
- CSS variables for theming
- Minified assets
- Optimized font loading
- Efficient animations

## Browser Support

- Chrome (last 2 versions)
- Firefox (last 2 versions)
- Safari (last 2 versions)
- Edge (last 2 versions)
- iOS Safari (last 2 versions)
- Android Chrome (last 2 versions)

## License

This project is licensed under the MIT License.

## Contact

For any queries or support, please contact:
support@metaversesolutions.com 