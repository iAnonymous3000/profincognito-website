# ProfIncognito Website

A privacy-focused personal website built with Hugo WonderMod theme, showcasing security research, chess strategy, and digital rights advocacy.

## Overview

[profincognito.me](https://profincognito.me) serves as a platform for:
- Privacy Research & Security Strategies
- Open Source Security Tools
- Chess-Inspired Security Thinking
- Digital Rights Education
- Privacy-Preserving Technologies

## Tech Stack

- **Static Site Generator**: Hugo Extended v0.123.6
- **Theme**: [WonderMod](https://github.com/Wonderfall/hugo-WonderMod) (Privacy-hardened fork of PaperMod)
- **Hosting**: Cloudflare Pages
- **DNS & Security**: Cloudflare
- **Deployment**: Automated via Cloudflare Pages
- **Email**: Cloudflare Email Routing

## Privacy Features

Built with privacy-first principles:
- No JavaScript tracking
- No external dependencies
- No cookies
- No local storage
- Minimal external requests
- Strong Content Security Policy
- Privacy-preserving contact methods
- Secure email routing

## Local Development

### Prerequisites
- Hugo Extended v0.123.6+
- Git

### Setup
```bash
# Clone the repository
git clone https://github.com/iAnonymous3000/profincognito-website.git

# Enter directory
cd profincognito-website

# Initialize theme
git submodule update --init --recursive

# Start development server
hugo server -D
```

### Build
```bash
# Production build
hugo --minify
```

## Deployment

Automatic deployment via Cloudflare Pages:
1. Push to main branch
2. Cloudflare Pages builds site
3. Changes deploy to profincognito.me

### Build Settings
- Build command: `hugo --gc --minify`
- Build output directory: `public`
- Hugo version: `0.123.6`

## Security

### Security Headers
- Strict Content Security Policy
- X-Frame-Options
- X-Content-Type-Options
- Referrer-Policy
- Permissions-Policy

## Contributions

While this is a personal website, bug reports are welcome:
1. Submit via GitHub Issues
2. Use security advisory for vulnerabilities
3. Contact through secure channels for sensitive issues

## Support

Support privacy research and development:
- Code contributions
- Security research collaboration
- Privacy-preserving cryptocurrency donations
  - Monero (XMR)
  - Zcash (ZEC)

## License

- Code: [AGPL-3.0](LICENSE)
- Content: CC BY-SA 4.0
- Theme: MIT (WonderMod)

## Credits

- Hugo Team
- WonderMod Theme
- Privacy & Security Community

---

© 2024 ProfIncognito. Advancing privacy and digital rights.
