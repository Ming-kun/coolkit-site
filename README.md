# CoolKit OEM/ODM Website

Static website for CoolKit's IoT smart device OEM/ODM business.

## Overview

CoolKit (eWeLink) is an IoT Devices Turnkey Solution Provider and Authorized Smart Home IoT Solution Provider (ASP) for Google Home & Amazon Alexa. This site showcases our OEM/ODM capabilities, product range (300+ SKUs), manufacturing facility, and global platform integrations.

## Structure

```
coolkit-site/
├── index.html          # Main website (single-page)
├── README.md
└── images/
    ├── logo.svg        # CoolKit logo
    ├── favicon.png     # Browser tab icon
    ├── hero.jpg        # Hero section image
    ├── about-*.jpg     # About section cards (factory, R&D, global, QA)
    ├── platform-banner.jpg  # Platform integrations banner
    ├── prod-*.png      # Product images (20 products)
    └── partner-*.png   # Cooperation partner logos (8 partners)
```

## Deployment

Hosted on [Vercel](https://vercel.com). Any push to `main` triggers auto-deployment.

## Local Preview

```bash
# Option 1: Open directly
open index.html

# Option 2: Local server (better for testing)
python3 -m http.server 8080
# then visit http://localhost:8080
```

## Tech Stack

- Pure HTML / CSS / JavaScript (no framework, no build step)
- Fonts: Outfit + DM Sans (Google Fonts)
- Responsive design (desktop + tablet + mobile)
- VR Factory Tour module: Pannellum.js (coming soon)

## Contact

- OEM/ODM: oemodm@coolkit.cn
- Cloud API: bd@coolkit.cn
- Website: [ewelink.cc](https://ewelink.cc)
