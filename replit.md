# Rahul Chadar - Portfolio Website

## Overview

This is a personal portfolio website for Rahul Chadar, a Machine Learning Enthusiast and Web Developer. The site is built as a static single-page application using vanilla HTML, CSS, and JavaScript with modern animations and responsive design. It showcases projects, skills, and contact information in an interactive and visually appealing format.

## System Architecture

### Frontend Architecture
- **Single-page application (SPA)** built with vanilla HTML, CSS, and JavaScript
- **Component-based structure** with distinct sections (Hero, About, Projects, Contact)
- **Mobile-first responsive design** approach
- **Progressive enhancement** with JavaScript animations and interactions

### Technology Stack
- **HTML5** for semantic markup and structure
- **CSS3** with modern features (Grid, Flexbox, CSS Variables, Transforms)
- **Vanilla JavaScript** for interactivity and animations
- **External libraries**: AOS (Animate On Scroll), Font Awesome icons, Google Fonts

## Key Components

### 1. Navigation System
- Fixed header with smooth scrolling navigation
- Active section highlighting based on scroll position
- Mobile hamburger menu for responsive design
- Backdrop blur effect on scroll

### 2. Hero Section
- Animated typing effect for name display
- Fade-in animations using AOS library
- Call-to-action buttons with hover effects
- Placeholder for profile image

### 3. Interactive Features
- Smooth scroll behavior between sections
- Animated skill bars and counters
- Hover effects on interactive elements
- Mobile-responsive design with touch-friendly interactions

### 4. Animation System
- AOS (Animate On Scroll) for section animations
- Custom JavaScript for typing effects
- CSS transitions and transforms for micro-interactions
- Scroll-triggered animations and effects

## Data Flow

### Static Content Flow
1. HTML provides semantic structure and initial content
2. CSS handles styling, layout, and basic animations
3. JavaScript enhances with dynamic behaviors and complex animations
4. External libraries provide additional animation capabilities

### User Interaction Flow
1. User scrolls or navigates → JavaScript detects scroll position
2. Active navigation updates → CSS classes applied for visual feedback
3. Sections come into view → AOS triggers entrance animations
4. User interacts with elements → Hover/click effects activate

## External Dependencies

### CDN Resources
- **Google Fonts (Poppins)** - Typography
- **Font Awesome 6.4.0** - Icons and visual elements
- **AOS (Animate On Scroll) 2.3.1** - Scroll-based animations

### Rationale for External Dependencies
- **Google Fonts**: Provides consistent, web-optimized typography across all devices
- **Font Awesome**: Offers scalable vector icons without additional image assets
- **AOS**: Simplifies complex scroll-based animations with minimal configuration

## Deployment Strategy

### Static Hosting
- **Platform**: Replit (web hosting)
- **Architecture**: Client-side only, no server required
- **Assets**: All resources served from CDN or inline
- **Performance**: Optimized for fast loading with minimal dependencies

### Deployment Benefits
- **Simplicity**: No backend infrastructure required
- **Cost-effective**: Free hosting on Replit
- **Fast loading**: Static assets with CDN optimization
- **Easy maintenance**: Simple file structure for updates

## Changelog

```
Changelog:
- July 01, 2025. Initial setup
- July 01, 2025. Updated with user's actual content:
  * Changed navigation logo from "RC" to "Rahul Chadar"
  * Replaced placeholder profile photo with actual passport photo
  * Added two additional photos in gallery section with animations
  * Replaced all project cards with user's actual 7 projects
  * Removed false statistics (projects completed, experience, clients)
  * Removed small left-side photos, kept only right-side gallery
  * Cleaned up layout and removed unnecessary spacing
```

## User Preferences

```
Preferred communication style: Simple, everyday language.
```

---

### Technical Notes

- The website follows modern web standards with semantic HTML5
- CSS uses custom properties for maintainable theming
- JavaScript is modular with separate functions for different features
- All animations are hardware-accelerated using CSS transforms
- The design is fully responsive with mobile-first approach
- Performance optimized with minimal external dependencies