# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a multi-page static website for BOLA JAPAN, a mullet roe import company. The site is built with vanilla HTML, CSS, and JavaScript with no build tools or package managers.

## Development Commands

Since this is a static website with no build system:

- **Local development**: Use a local server (e.g., Live Server extension in VS Code, Python's `python -m http.server`, or Node's `npx serve`)
- **No build process**: Files are served directly without compilation
- **No package manager**: All dependencies are loaded via CDN

## Architecture

### Multi-Page Structure
- `index.html` - Redirect page to home.html
- `home.html` - Landing page with hero section and quick features
- `about.html` - Company information and values
- `products.html` - Product catalog with detailed specifications
- `process.html` - Manufacturing process and traditional methods
- `gallery.html` - Product gallery with filtering functionality
- `contact.html` - Contact form, company details, and FAQ
- `styles.css` - Primary styles with multi-page specific sections
- `mobile.css` - Mobile-specific styles and overrides
- `script.js` - Enhanced functionality for multi-page navigation and features
- `logo-refined.svg` / `logo.svg` - Company logos
- `images/` - Product and gallery images
- Test files: `test.html`, `mobile-test.html`, `menu-test.html` for development

### Design System
- **Typography**: Inter font family from Google Fonts
- **Icons**: Font Awesome 6.0 via CDN
- **Colors**: Primary orange (#ff6b35), gradient backgrounds (blue-purple)
- **Responsive**: Mobile-first approach with hamburger menu

### Key Features
- **Smooth scrolling navigation** with fixed navbar
- **Intersection Observer animations** for scroll-triggered effects
- **Parallax effects** on floating elements
- **Form validation** for contact section
- **Mobile responsive** with dedicated CSS file
- **Japanese language** content throughout

### JavaScript Architecture
- **Multi-page navigation**: Active page detection and navigation highlighting
- **Page-specific initialization**: Different functionality per page
- **Enhanced form validation**: Real-time validation with Japanese messages
- **Gallery filtering**: Dynamic content filtering on gallery page
- **FAQ accordion**: Interactive expand/collapse functionality
- **Animation systems**: Intersection Observer for scroll animations
- **Mobile menu**: Hamburger toggle with active states
- **Form handling**: Enhanced contact form with loading states
- **Page transitions**: Smooth loading between pages

### Styling Organization
- `styles.css`: Main styles, animations, desktop layout
- `mobile.css`: Mobile overrides and responsive adjustments
- **CSS Grid/Flexbox**: Modern layout techniques
- **CSS animations**: Keyframes and transitions for interactive effects

## Page Structure
1. **Home Page**: Hero section, quick features, and call-to-action
2. **About Page**: Company mission, values, and detailed company information
3. **Products Page**: Detailed product catalog with specifications and categories
4. **Process Page**: Manufacturing timeline, traditional methods, and quality assurance
5. **Gallery Page**: Filterable image gallery with overlay information
6. **Contact Page**: Multiple contact methods, enhanced form, and FAQ section

## Key Features
- **Responsive design**: Mobile-first approach with hamburger menu
- **Multi-page navigation**: Smooth transitions between pages
- **Interactive elements**: Gallery filters, FAQ accordion, form validation
- **Animation system**: Scroll-triggered animations using Intersection Observer
- **Form enhancements**: Real-time validation, loading states, notifications
- **Active navigation**: Current page highlighting in navigation menu

## Company Information
- **Name**: 合同会社 BOLA JAPAN
- **Business**: Mullet roe (烏魚子) import and sales
- **Established**: April 16, 2025
- **Location**: Tokyo, Japan