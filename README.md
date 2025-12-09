# ReMarkable Church AI

Building ReMarkable AI 21st Churches

## 🚀 Live Site

Visit the live application at: [https://remarkable-church-ai.vercel.app](https://remarkable-church-ai.vercel.app)

### 📱 QR Code

Scan the QR code to access the app on your mobile device:

![QR Code](qr-code.png)

**Available formats:**
- `qr-code.png` - PNG image (370x370px)
- `qr-code.svg` - SVG vector image (scalable)

## 📋 Project Overview

This is a no-build prototype for ReMarkable Church AI (Project 13). The application is a single-page HTML file that uses:
- **React 18** - UI framework loaded via CDN
- **Tailwind CSS** - Styling via CDN
- **Babel Standalone** - In-browser JSX compilation
- **Client-side only** - No build process required

## 🛠️ Technical Stack

- HTML5
- React 18 (CDN)
- React DOM 18 (CDN)
- Tailwind CSS (CDN)
- Babel Standalone (CDN)

## 📦 Deployment

The site is automatically deployed to Vercel on every push to the `main` branch.

### Deployment URL
- **Production**: https://remarkable-church-ai.vercel.app

## 🏗️ Project Structure

```
remarkable-church-ai/
├── index.html          # Main application file (single-page app)
├── .gitignore          # Git ignore rules
└── README.md           # This file
```

## 🚀 Getting Started

Since this is a no-build project, you can simply:

1. Open `index.html` in any modern web browser
2. Or serve it with any static file server:
   ```bash
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

## 🔧 Development

No build process needed! Just edit `index.html` and refresh your browser.

The application uses:
- Inline JSX that's compiled in the browser
- CDN-hosted dependencies
- No npm packages or build tools

## 📝 Recent Changes

### HTML Fixes (PR #9)
- ✅ Removed YAML front-matter (`---` markers)
- ✅ Removed duplicate `<html>` tag
- ✅ Fixed escaped quotes throughout the file
- ✅ Valid HTML5 structure restored

## 🤝 Contributing

1. Create a feature branch
2. Make your changes
3. Submit a PR to `main`
4. Vercel will automatically deploy a preview

## 📄 License

All rights reserved.

## 👤 Author

**jeanvoltaire01-dev**
- GitHub: [@jeanvoltaire01-dev](https://github.com/jeanvoltaire01-dev)
