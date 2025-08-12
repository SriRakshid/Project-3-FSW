# Responsive One-Page Website

A modern, responsive single-page website for a fictional design agency with sticky navigation, smooth scrolling, and a hamburger menu for mobile devices.

## Features

### ✅ Page Structure
- **HTML5 Semantic Tags**: Uses proper semantic structure with `<header>`, `<nav>`, `<main>`, `<section>`, and `<footer>`
- **5 Sections**: Home, About, Services, Portfolio, and Contact with unique IDs
- **Well-structured Content**: Organized and accessible content layout

### ✅ Sticky Navigation Bar
- **Sticky Positioning**: Navigation stays at the top when scrolling
- **Semi-transparent Background**: Modern glassmorphism effect with backdrop blur
- **Brand Logo**: Creative Studio branding with styled typography
- **Navigation Links**: Smooth scrolling to all sections
- **Visual Design**: Contrasting colors, rounded corners, and subtle shadows

### ✅ Smooth Scrolling
- **CSS Smooth Scroll**: Native smooth scrolling behavior
- **JavaScript Enhancement**: Additional smooth scrolling functionality
- **Active Navigation**: Highlights current section in navigation

### ✅ Hamburger Menu (Mobile-First Design)
- **Responsive Breakpoint**: 768px and below
- **Hidden Checkbox**: CSS-only hamburger menu using `:checked` pseudo-class
- **Smooth Transitions**: Fade and slide animations
- **Full-width Links**: Mobile-optimized navigation layout
- **Animated Icon**: Hamburger transforms to X when opened

### ✅ Responsive Design
- **Flexbox & CSS Grid**: Modern layout techniques
- **Mobile-First Approach**: Designed for mobile, enhanced for desktop
- **Media Queries**: Adapts layout for mobile, tablet, and desktop
- **Readable Typography**: Optimized text sizes for all devices

### ✅ Visual Design & Interactivity
- **Google Fonts**: Poppins font family for modern typography
- **Hover Effects**: Interactive elements with smooth transitions
- **Color Scheme**: Professional blue and dark gray palette
- **Animations**: Subtle animations and transitions throughout
- **Modern UI**: Clean, professional design with modern aesthetics

## File Structure

```
responsive-website/
├── index.html          # Main HTML file with semantic structure
├── style.css           # CSS with responsive design and animations
├── script.js           # JavaScript for interactivity
└── README.md           # Project documentation
```

## Sections

### 1. Home Section (`#home`)
- Hero content with call-to-action buttons
- Gradient background with modern design
- Animated graphics and typography

### 2. About Section (`#about`)
- Company story and mission
- Statistics showcase (projects, clients, experience)
- Visual elements with icons

### 3. Services Section (`#services`)
- 4 service cards with icons
- Hover effects and animations
- Responsive grid layout

### 4. Portfolio Section (`#portfolio`)
- Project showcase with hover overlays
- Interactive portfolio items
- Modern card design

### 5. Contact Section (`#contact`)
- Contact information with icons
- Functional contact form
- Responsive two-column layout

## Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: 
  - Flexbox and CSS Grid for layout
  - CSS animations and transitions
  - Media queries for responsiveness
  - CSS custom properties
- **JavaScript**: 
  - Smooth scrolling functionality
  - Form handling
  - Interactive animations
  - Scroll-to-top button
- **External Libraries**:
  - Google Fonts (Poppins)
  - Font Awesome (Icons)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Features in Detail

### Navigation System
- **Sticky Header**: Uses `position: sticky` for modern browsers
- **Backdrop Filter**: Glassmorphism effect with blur
- **Active States**: JavaScript tracks scroll position for active navigation
- **Mobile Menu**: CSS-only hamburger menu with smooth animations

### Responsive Breakpoints
- **Mobile**: < 768px (hamburger menu, single column layouts)
- **Tablet**: 768px - 1024px (adjusted spacing and typography)
- **Desktop**: > 1024px (full layout with hover effects)

### Animations
- **Scroll Reveal**: Elements animate in as they enter viewport
- **Hover Effects**: Interactive elements respond to user interaction
- **Smooth Transitions**: All interactive elements have smooth transitions
- **Loading Animation**: Page fade-in on load

### Accessibility
- **Semantic HTML**: Proper heading hierarchy and landmarks
- **Focus States**: Visible focus indicators for keyboard navigation
- **ARIA Labels**: Proper labeling for screen readers
- **Color Contrast**: WCAG compliant color combinations

## How to Use

1. **Open the Website**: Open `index.html` in a web browser
2. **Navigate**: Use the navigation menu to jump to different sections
3. **Mobile Experience**: Resize browser or view on mobile device to see hamburger menu
4. **Interact**: Hover over elements to see animations and effects
5. **Contact Form**: Fill out the contact form (demo functionality)

## Customization

### Colors
The website uses a consistent color scheme defined in CSS:
- Primary Blue: `#3498db`
- Dark Blue: `#2980b9`
- Dark Gray: `#2c3e50`
- Light Gray: `#7f8c8d`

### Typography
- Font Family: Poppins (Google Fonts)
- Weights: 300, 400, 500, 600, 700

### Layout
- Container max-width: 1200px
- Section padding: 80px (mobile: 60px)
- Grid gaps: 2rem (mobile: 1rem)

## Performance Features

- **Optimized Images**: Uses Font Awesome icons instead of images
- **Minimal JavaScript**: Lightweight, efficient code
- **CSS Optimization**: Efficient selectors and minimal repaints
- **Smooth Animations**: Hardware-accelerated CSS transitions

## Future Enhancements

- Add real images to portfolio section
- Implement actual form submission functionality
- Add more interactive animations
- Include a blog section
- Add dark mode toggle
- Implement lazy loading for better performance

## License

This project is open source and available under the MIT License.

---

**Created with ❤️ for modern web development**
