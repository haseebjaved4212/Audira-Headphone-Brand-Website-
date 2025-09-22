# 🎧 Audira - Premium Headphone Brand Website

A modern, responsive, and animated website for Audira premium headphones, featuring smooth scrolling animations, dynamic content transitions, and an immersive user experience.

## ✨ Features

###  Design & User Experience

- **Modern UI/UX**: Clean, minimalist design with premium aesthetics
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Scrolling**: Implemented using GSAP ScrollSmoother for buttery smooth navigation
- **Interactive Animations**: Dynamic headphone animations that respond to scroll position
- **Glass Morphism Effects**: Modern UI elements with backdrop filters and transparency

###  Technical Features

- **GSAP Animations**: Advanced scroll-triggered animations using GSAP library
- **Performance Optimized**: Efficient animations with proper easing and timing
- **Cross-Browser Compatible**: Works seamlessly across all modern browsers
- **SEO Friendly**: Semantic HTML structure with proper meta tags
- **Accessibility Ready**: Built with accessibility best practices

###  Responsive Design

- **Mobile-First Approach**: Optimized for mobile devices with touch-friendly interfaces
- **Tablet Optimization**: Special layouts for tablet views (769px - 990px)
- **Desktop Experience**: Full-featured desktop experience with advanced animations
- **Adaptive Content**: Content adapts to screen size while maintaining visual hierarchy

## 🛠️ Technologies Used

### Frontend

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with custom properties, flexbox, and grid
- **JavaScript**: ES6+ features for interactive functionality
- **GSAP (GreenSock)**: Advanced animation library
  - ScrollTrigger: Scroll-based animations
  - ScrollSmoother: Smooth scrolling experience
  - SplitText: Text animation effects

### Assets

- **Custom Typography**: Google Fonts (DM Sans, Outfit)
- **Optimized Images**: PNG and JPEG formats for product showcases
- **Video Content**: MP4 video for immersive product demonstrations
- **Vector Graphics**: SVG icons for social media and UI elements

## Preview 
- [Audira Headphone Brand]()

## 📂 Project Structure

```
Audira-Headphone-Brand/
├── index.html              # Main HTML file
├── style.css               # Main stylesheet with responsive design
├── script.js               # JavaScript animations and interactions
├── README.md               # Project documentation
└── images/                 # Asset directory
    ├── logo.png            # Brand logo
    ├── brown.png           # Brown headphone variant
    ├── black.png           # Black headphone variant
    ├── green.png           # Green headphone variant
    ├── img1.jpeg           # Product showcase image 1
    ├── img2.jpeg           # Product showcase image 2
    ├── img3.jpeg           # Product showcase image 3
    ├── img4.jpg            # Pure Escape section image
    ├── video.mp4           # Product demonstration video
    ├── fb.png              # Facebook icon
    └── insta.png           # Instagram icon
```

## 🎨 Sections Overview

### 1. **Hero Section**

- Dynamic animated heading with split-text effects
- Animated headphone showcase with scroll-based transformations
- Call-to-action button with hover effects

### 2. **True Clarity Section**

- Product feature highlights in responsive grid layout
- Animated content boxes with staggered animations
- Clear value proposition with engaging copy

### 3. **Masterbeat Section**

- Video showcase with autoplay and loop
- Side-by-side content layout
- Responsive video player with proper aspect ratios

### 4. **Image Gallery**

- Rotated image layouts with dynamic positioning
- Scroll-triggered reveal animations
- Mobile-friendly stacked layout

### 5. **Top Picks Section**

- Product showcase with pricing
- Grid layout that adapts to screen size
- Hidden middle product on desktop for design balance

### 6. **Pure Escape Section**

- Card-style layout for tablet and mobile
- Image and content side-by-side arrangement
- Glass morphism design elements

### 7. **Footer**

- Brand logo and social media links
- Responsive layout with proper spacing
- Professional contact information display

## 🚀 Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, for development)

### Installation & Setup

1. **Clone or Download the Project**

   ```bash
   # If using Git
   git clone <repository-url>

   # Or download and extract the ZIP file
   ```

2. **Navigate to Project Directory**

   ```bash
   cd Audira-Headphone-Brand
   ```

3. **Open in Browser**
   ```bash
   # Option 1: Double-click index.html
   # Option 2: Use a local server
   python -m http.server 8000
   # Then visit: http://localhost:8000
   ```

### Development Setup

For development with live reloading:

```bash
# Using Live Server (VS Code Extension)
# Or using any local development server
npx live-server
```

##  Responsive Breakpoints

- **Mobile**: ≤ 768px
- **Tablet**: 769px - 990px
- **Desktop**: ≥ 991px

Each breakpoint has optimized:

- Typography scaling
- Layout arrangements
- Animation behaviors
- Touch interactions

## ⚡ Performance Optimizations

### Images

- Optimized file sizes without quality loss
- Proper aspect ratios for all screen sizes
- Lazy loading for better initial page load

### Animations

- Hardware-accelerated CSS transforms
- GSAP's efficient animation engine
- Reduced motion preferences support
- Conditional animations based on screen size

### Code

- Minified external libraries
- Efficient CSS with minimal redundancy
- Optimized JavaScript execution

## 🎯 Browser Support

- **Chrome**: 90+
- **Firefox**: 85+
- **Safari**: 14+
- **Edge**: 90+
- **Mobile Browsers**: iOS Safari 14+, Chrome Mobile 90+

## 🔧 Customization Guide

### Colors

Update CSS custom properties in `:root`:

```css
:root {
  --bg-color: #f5ece4; /* Background color */
  --primary-color: #734425; /* Primary brand color */
  --secondary-color: #c26819; /* Secondary/accent color */
  --black: #2e2e2e; /* Text color */
}
```

### Typography

Modify font imports and CSS font-family declarations:

```css
/* Google Fonts import */
@import url("https://fonts.googleapis.com/css2?family=DM+Sans:...");

/* Font variables */
--heading-font: "Outfit", sans-serif;
```

### Animations

Adjust GSAP timeline settings in `script.js`:

```javascript
// Modify scroll trigger settings
scrollTrigger: {
  trigger: "#section2",
  start: "top bottom",     // When animation starts
  end: "center center",    // When animation ends
  scrub: true,            // Smooth scrubbing
}
```

##  Troubleshooting

### Common Issues

1. **Animations not working**

   - Check GSAP library loading
   - Verify ScrollTrigger registration
   - Check console for JavaScript errors

2. **Responsive layout issues**

   - Clear browser cache
   - Check viewport meta tag
   - Verify CSS media query syntax

3. **Images not displaying**
   - Check file paths and names
   - Verify image file formats
   - Ensure proper folder structure

##  License

This project is open source and available for use and learning.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request. For major changes, please open an issue first to discuss what you would like to change.

### Development Guidelines

1. Follow existing code style and conventions
2. Test responsive design on multiple devices
3. Ensure animations are smooth and performant
4. Update documentation for any new features

##  Support

If you encounter any issues or have questions:

1. Check the troubleshooting section above
2. Open an issue on the project repository
3. Contact the development team

##  Acknowledgments

- **GSAP**: For providing excellent animation libraries
- **Google Fonts**: For beautiful typography options
- **Design Inspiration**: Modern premium brand websites


---

Made with ❤️ for modern web experiences
