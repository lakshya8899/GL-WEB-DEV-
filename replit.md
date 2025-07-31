# Lakshya Goyal Portfolio

## Overview

This is a personal portfolio website for Lakshya Goyal, a penultimate-year Bachelor of IT student and aspiring web developer. The site showcases his educational journey from TAFE certificates through university studies, highlighting projects and professional experience. Built as a single-page application using vanilla HTML, CSS, and JavaScript with no external frameworks.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Single-page application (SPA)** built with vanilla HTML5, CSS3, and JavaScript
- **Responsive design** using CSS Grid and Flexbox for cross-device compatibility
- **Component-based structure** with distinct sections (Hero, About, Projects, Experience, Contact)
- **Mobile-first approach** with hamburger navigation for smaller screens

### Styling Strategy
- **CSS Custom Properties (Variables)** for consistent theming and easy maintenance
- **Modern CSS features** including Grid, Flexbox, and CSS transitions
- **Font Awesome icons** for visual enhancement
- **No CSS frameworks** - custom styling throughout for full control

### JavaScript Functionality
- **Vanilla JavaScript** for all interactions
- **Event-driven architecture** for user interactions
- **Smooth scrolling navigation** between sections
- **Dynamic content switching** for project tabs

## Key Components

### Navigation System
- **Fixed navigation bar** with smooth scroll-to-section functionality
- **Mobile-responsive hamburger menu** that toggles on smaller screens
- **Active state management** for navigation links

### Hero Section
- **Personal branding area** with name, title, and professional tagline
- **Call-to-action buttons** for projects, resume download, and contact
- **Profile image placeholder** for visual identity

### Project Showcase
- **Tabbed interface** organizing projects by educational level (Cert III, Cert IV, Diploma, University)
- **Dynamic content switching** using JavaScript tab functionality
- **Progressive skill demonstration** showing growth through educational journey

### Interactive Elements
- **Mobile menu toggle** with animated hamburger icon
- **Tab-based project filtering** for organized content display
- **Smooth scroll behavior** for enhanced user experience

## Data Flow

### User Interaction Flow
1. **Initial Load**: Static HTML content renders with CSS styling
2. **Navigation**: JavaScript handles smooth scrolling between sections
3. **Mobile Menu**: Toggle functionality manages responsive navigation
4. **Project Tabs**: Dynamic content switching without page reload
5. **External Links**: Resume download and contact actions

### Event Management
- **Click events** for navigation, mobile menu, and project tabs
- **Scroll events** for smooth navigation behavior
- **Responsive events** for mobile menu interactions

## External Dependencies

### CDN Resources
- **Font Awesome 6.4.0**: Icon library for visual elements
- **Google Fonts** (via system fonts): Typography enhancement

### Static Assets
- **Resume PDF**: Downloadable document stored in assets folder
- **Profile images**: Placeholder for personal branding
- **Project screenshots**: Visual representations of work

## Deployment Strategy

### Static Site Hosting
- **Client-side only**: No server-side processing required
- **Static file serving**: HTML, CSS, JavaScript, and assets
- **CDN compatibility**: All external resources loaded via CDN
- **Cross-browser support**: Modern browser features with graceful degradation

### File Structure
- **Root level**: Main HTML file as entry point
- **Separate concerns**: CSS and JavaScript in dedicated files
- **Assets folder**: Static resources (resume, images)
- **Modular approach**: Easy to maintain and extend

### Performance Considerations
- **Minimal dependencies**: Only essential external resources
- **Optimized images**: Placeholder system for efficient loading
- **CSS variables**: Efficient styling with minimal redundancy
- **Vanilla JavaScript**: No framework overhead for faster loading

## Development Approach

The portfolio follows a **progressive enhancement** strategy, starting with semantic HTML structure, adding CSS for presentation, and JavaScript for enhanced interactions. This ensures the site remains functional even if JavaScript fails to load, providing a robust user experience across all conditions.