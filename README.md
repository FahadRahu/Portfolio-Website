# 🚀 Spectacular Portfolio Website

> A stunning, interactive portfolio showcasing modern web development techniques with glassmorphism, particle effects, and smooth animations.

![Portfolio Preview](https://img.shields.io/badge/Status-Live-success?style=for-the-badge)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)

## ✨ Features

### 🎨 Visual Effects
- **Particle System Canvas** - Interactive floating particles that respond to user movement
- **Custom Cursor** - Glowing dot with smooth trailing outline for enhanced interactivity
- **Glassmorphism Design** - Frosted glass aesthetic with backdrop blur effects
- **Gradient Orbs** - Animated floating color blobs creating depth
- **Smooth Animations** - Carefully crafted entrance and hover animations throughout

### 🌙 Theme System
- **Dark/Light Mode Toggle** - Seamless theme switching with localStorage persistence
- **Animated Theme Transition** - Smooth color transitions when switching modes
- **System Preference Detection** - Respects user's OS theme preference

### 🎯 Interactive Elements
- **Typing Effect** - Dynamic role cycling in hero section
- **Animated Statistics** - Number counters that animate on scroll
- **Skill Bars** - Animated progress bars showing proficiency levels
- **Timeline Progress** - Visual scroll indicator for experience timeline
- **Magnetic Buttons** - Buttons that respond to mouse movement
- **Tilt Cards** - 3D card effects on hover
- **Project Overlays** - Reveal links and information on hover

### 🎨 Design Philosophy
- **Cosmic Theme** - Deep space aesthetics with futuristic tech elements
- **Responsive Design** - Fully responsive across all devices
- **Accessibility** - ARIA labels and semantic HTML
- **Performance Optimized** - Smooth 60fps animations

## 🚀 Quick Start

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/fahadrahu/portfolio-website.git

# Navigate to project directory
cd portfolio-website

# Install dependencies
npm install

# Start development server
npm run dev
```

The site will open automatically at `http://localhost:3000`

## 📜 Available Scripts

```bash
# Start development server with hot reload
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## 🎨 Customization

### Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --primary-purple: #7c3aed;
    --primary-cyan: #06b6d4;
    --accent-green: #10b981;
    /* ... more colors */
}
```

### Content
- **Personal Info**: Edit `index.html` sections
- **Projects**: Modify project cards in the projects section
- **Skills**: Update skill bars and tech stacks
- **Experience**: Add/edit timeline items

### Animations
Adjust animation timings in `script.js`:
```javascript
const typingSpeed = 100; // Milliseconds per character
const deleteSpeed = 50;  // Milliseconds per character deletion
```

## 📁 Project Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── styles.css          # Complete stylesheet with all effects
├── script.js           # Interactive features and animations
├── vite.config.js      # Vite configuration
├── package.json        # Dependencies and scripts
├── .gitignore          # Git ignore rules
└── README.md           # This file
```

## 🎯 Key Sections

1. **Hero Section** - Eye-catching landing with animated tech orbit
2. **About Section** - Personal introduction with certifications
3. **Experience Section** - Professional timeline with glassmorphism cards
4. **Projects Section** - Featured work with hover effects
5. **Skills Section** - Technical abilities with animated progress bars
6. **Contact Section** - Multiple contact methods with magnetic cards

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with animations
- **JavaScript (ES6+)** - Interactive features
- **Vite** - Build tool and dev server
- **Font Awesome** - Icon library
- **Google Fonts** - Typography (Space Grotesk, Inter, JetBrains Mono)

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ⚠️ IE11 (not supported)

## 🎨 Color Palette

| Color | Hex | Usage |
|-------|-----|-------|
| Primary Purple | `#7c3aed` | Primary accent, gradients |
| Primary Cyan | `#06b6d4` | Secondary accent, links |
| Accent Green | `#10b981` | Success states, highlights |
| Accent Pink | `#ec4899` | Special highlights |
| Dark Background | `#0a0a0f` | Main background (dark mode) |
| Light Background | `#fafafa` | Main background (light mode) |

## ⚡ Performance Tips

- All animations use CSS transforms (GPU accelerated)
- Particle count scales with screen size
- Images lazy load for faster initial load
- Minimal JavaScript for core functionality
- CSS is optimized for production builds

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

MIT License - feel free to use this template for your own portfolio!

## 👤 Author

**Fahad Rahu**
- LinkedIn: [@fahadrahu](https://linkedin.com/in/fahadrahu)
- GitHub: [@fahadrahu](https://github.com/fahadrahu)
- Email: fahadrahu@gmail.com

## 🙏 Acknowledgments

- Design inspiration from modern web trends
- Font Awesome for icons
- Google Fonts for typography
- The web development community

## 🎉 Features Highlight

### Advanced Animations
- Particle system with connection lines
- Smooth scroll-based animations
- Typing effect with multiple roles
- Counter animations for statistics
- Timeline progress indicator
- Skill bar animations

### Interactive Elements
- Custom cursor with magnetic effect
- Tilt effect on cards
- Hover transitions on all interactive elements
- Mobile-friendly hamburger menu
- Smooth section navigation
- Scroll-to-top button with progress ring

### Design Details
- Glassmorphism throughout
- Gradient text effects
- Floating geometric shapes
- Noise overlay for texture
- Responsive grid layouts
- Mobile-first approach

---

Built with ❤️ and lots of ☕ by Fahad Rahu
