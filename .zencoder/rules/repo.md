# Repository Information

## Project Type
Static Portfolio Website

## Technology Stack
- **Frontend**: HTML5, CSS3, Tailwind CSS
- **JavaScript**: Vanilla JavaScript
- **External Libraries**:
  - Tailwind CSS (via CDN)
  - Font Awesome 6.4.0 (icons)
  - AOS (Animate On Scroll) 2.3.1
  - Google Fonts (Inter, Playfair Display)

## Project Structure
```
d:\Zen Coder Projects\Graphic Portfolio\
├── index.html          (Main portfolio page)
├── script.js           (JavaScript functionality)
├── .vscode/            (VS Code settings)
├── .zencoder/          (Zencoder configuration)
├── pics/               (Image assets)
│   ├── my personal img/
│   ├── my project img/
│   │   ├── Behance Project/
│   │   ├── Social media/
│   │   └── Tasks/
│   └── img for website/
└── README.md           (Project documentation)
```

## Key Features
- Responsive hero section with animated profile image
- Portfolio gallery with filtering
- Skills showcase with progress bars
- Contact form
- Dark gradient theme with purple/blue color scheme
- Smooth animations and transitions
- Mobile-optimized design

## Target Framework (for E2E Testing)
**Playwright** (default - no existing test configuration found)

## Recent Modifications
- Enhanced home section profile image styling to improve visual presentation
- Added breathing room through margin and padding
- Improved glow effect visibility
- Made image container less constrictive with softer borders

## Development Server
- Runs on `http://localhost:8000`
- Python HTTP Server

## Notes
- No package.json (not a Node.js project)
- All styling uses Tailwind CSS utility classes and custom CSS
- Project uses CDN for all external resources