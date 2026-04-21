# ADL Business Consulting - Landing Page

This repository contains the landing page for **ADL Business Consulting**, configured for deployment on GitHub Pages with a custom domain.

## Custom Domain Configuration
The repository includes a `CNAME` file pointing to `www.adlbusinessconsulting.com`.

## How to Deploy
1. **Upload** `index.html` and `CNAME` to this repository.
2. **DNS Setup**: Ensure your domain registrar has the following:
   - **A Records** pointing to: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - **CNAME Record** for `www` pointing to `[your-username].github.io`.
3. **GitHub Settings**: Go to **Settings > Pages** and ensure "Enforce HTTPS" is checked once the certificate is generated.

## Technical Details
- Responsive HTML5/CSS3
- Glassmorphism UI elements
- Zero external dependencies (fast loading)
