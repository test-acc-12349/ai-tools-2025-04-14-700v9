# AI Tools Directory 🤖

> The ultimate directory of AI tools and resources for professionals and enthusiasts.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](http://makeapullrequest.com)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Directory Structure](#directory-structure)
- [Customization](#customization)
- [Deployment](#deployment)
- [Custom Domain Setup](#custom-domain-setup)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [Support](#support)

## Overview

AI Tools Directory is a responsive, modern directory website showcasing artificial intelligence tools and resources in a clean, three-column grid layout. Built with HTML5, CSS3, and vanilla JavaScript for optimal performance.

## Features

- 🎯 Responsive 3-column grid layout
- 🔍 Search functionality
- 🏷️ Category filtering
- 💨 Fast loading times
- 📱 Mobile-friendly design
- 🎨 Customizable styling
- 🔄 Easy content updates

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/ai-tools-directory.git
cd ai-tools-directory
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

## Directory Structure

```
ai-tools-directory/
├── assets/
│   ├── images/
│   ├── css/
│   └── js/
├── data/
│   └── directory-items.json
├── components/
├── pages/
├── public/
└── index.html
```

## Customization

### Adding Directory Items

1. Open `data/directory-items.json`
2. Add new items following this format:

```json
{
  "id": "unique-id",
  "title": "Tool Name",
  "description": "Tool description",
  "category": "Category",
  "url": "https://toolurl.com",
  "image": "/assets/images/tool-image.png"
}
```

### Modifying Categories

Edit the categories array in `js/config.js`:

```javascript
export const categories = [
  "Machine Learning",
  "Natural Language Processing",
  "Computer Vision",
  "Robotics"
];
```

### Updating Hero Section

Modify the hero section in `index.html`:

```html
<section class="hero">
  <h1>Your New Title</h1>
  <p>Your new description</p>
</section>
```

### Customizing Colors

Edit variables in `css/variables.css`:

```css
:root {
  --primary-color: #007bff;
  --secondary-color: #6c757d;
  --background-color: #ffffff;
  --text-color: #333333;
}
```

## Deployment

### GitHub Pages

1. Go to repository settings
2. Navigate to "Pages"
3. Select main branch
4. Save changes

### Netlify

1. Connect your GitHub repository
2. Configure build settings:
   - Build command: `npm run build`
   - Publish directory: `dist`
3. Deploy

## Custom Domain Setup

1. Purchase domain from registrar
2. Add DNS records:
```
A     @     185.199.108.153
A     @     185.199.109.153
CNAME www   yourusername.github.io
```
3. Add custom domain in repository settings

## Troubleshooting

### Common Issues

- **Images not loading**: Check path in `directory-items.json`
- **Search not working**: Clear browser cache
- **Styling issues**: Verify CSS compilation
- **Mobile layout problems**: Check media queries

### Debug Mode

Enable debug mode in console:
```javascript
localStorage.setItem('debug', 'true');
```

## Contributing

1. Fork the repository
2. Create feature branch
3. Commit changes
4. Push to branch
5. Create Pull Request

## Support

- 📚 [Documentation](https://github.com/yourusername/ai-tools-directory/wiki)
- 🐛 [Issue Tracker](https://github.com/yourusername/ai-tools-directory/issues)
- 💬 [Discussions](https://github.com/yourusername/ai-tools-directory/discussions)
- 📧 [Email Support](mailto:support@aitools.com)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

Made with ❤️ by [Your Name](https://yourwebsite.com)