# Public Assets

This directory contains all static assets for the BoardWise platform.

## Directory Structure

```
public/
├── icons/           # SVG icons used throughout the application
├── images/          # Illustrations and images
├── logos/           # Brand logos and favicons
└── README.md        # This file
```

## Icons (`/icons/`)

All icons are SVG format and use `currentColor` for easy theming.

### Available Icons:
- `security-shield.svg` - Security and protection icon
- `privacy-lock.svg` - Privacy and data protection icon
- `ai-brain.svg` - AI and intelligence icon
- `legal-scale.svg` - Legal and justice icon
- `document-check.svg` - Document verification icon
- `user-shield.svg` - User protection icon

### Usage:
```jsx
import Image from 'next/image'

<Image 
  src="/icons/security-shield.svg" 
  alt="Security" 
  width={24} 
  height={24} 
/>
```

## Images (`/images/`)

Illustrations and visual assets for the platform.

### Available Images:
- `hero-illustration.svg` - Main hero section illustration
- `dashboard-preview.svg` - Dashboard preview mockup
- `matt1.jpg` - Matt's photo for the founder statement section on homepage and about page
- `matt.JPG` - Previous version of Matt's photo (deprecated)
- `us1.jpg` - Professional using BoardWise platform for login page
- `us2.jpg` - Professional joining BoardWise platform for signup page
- `price.jpg` - Professional using platform for pricing section
- `feedback.jpg` - Professional feedback and testimonials for review section

### Usage:
```jsx
import Image from 'next/image'

<Image 
  src="/images/hero-illustration.svg" 
  alt="BoardWise Hero" 
  width={400} 
  height={300} 
/>
```

## Logos (`/logos/`)

Brand assets and favicons.

### Available Logos:
- `BoardWiseLogo.png` - Main logo for light backgrounds
- `BoardWiseLogoTransparent.png` - Transparent logo for dark backgrounds

### Usage:
```jsx
import Image from 'next/image'

<Image 
  src="/logos/BoardWiseLogo.png" 
  alt="BoardWise" 
  width={200} 
  height={80} 
/>
```

## Design System

### Colors:
- **Primary Blue**: `#0ea5e9` (sky-500)
- **Lavender**: `#a855f7` (purple-500)
- **Green**: `#10b981` (emerald-500)
- **Slate**: `#1e293b` (slate-800)

### Typography:
- **Font Family**: Inter, system-ui, sans-serif
- **Weights**: 400 (normal), 500 (medium), 600 (semibold), 700 (bold)

## Adding New Assets

1. **Icons**: Create SVG files with `currentColor` for stroke/fill
2. **Images**: Use SVG for illustrations, PNG/JPG for photos
3. **Logos**: Maintain consistent branding and sizing
4. **Optimization**: Use SVGO for SVG optimization
5. **Naming**: Use kebab-case for file names

## Performance

- All SVG assets are optimized for web use
- Icons use `currentColor` for dynamic theming
- Images are responsive and scalable
- Favicon is provided in SVG format for crisp display

## Accessibility

- All images include proper `alt` text
- Icons are semantic and meaningful
- Color contrast meets WCAG guidelines
- Scalable vector graphics for all screen sizes 