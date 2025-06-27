# AI for Future Minds - Educational Website

## Overview

This is a static educational website designed to empower rural youth with AI tools and knowledge. The project is part of a nonprofit initiative targeting rural school children in Taiwan, focusing on teaching them how to use AI tools effectively rather than building them. The website serves as both an informational platform and an interactive learning environment.

## System Architecture

### Frontend Architecture
- **Static Website**: Pure HTML/CSS/JavaScript implementation
- **CSS Framework**: Tailwind CSS for utility-first styling
- **Typography**: Google Fonts (Poppins) for enhanced readability
- **Icons**: Font Awesome for consistent iconography
- **Responsive Design**: Mobile-first approach with low-bandwidth compatibility

### Backend Architecture
- **Simple HTTP Server**: Python's built-in HTTP server for development
- **No Database**: Static content delivery without persistent data storage
- **No Authentication**: Public access educational content

## Key Components

### 1. Website Structure
- **Single Page Application**: All content on homepage (index.html)
- **Section-based Layout**: Navigation, Hero, Mission, Courses, Playground, Contact
- **Mobile-first Design**: Optimized for rural areas with limited bandwidth

### 2. Visual Design System
- **Color Palette**: 
  - Sky blue (#38BDF8) for primary elements
  - Yellow (#FCD34D) for highlights
  - Coral (#FB7185) for accents
  - Off-white (#F9FAFB) for backgrounds
- **Typography**: Poppins font family for all text
- **Spacing**: Consistent spacing using Tailwind utilities (py-20, mt-10)

### 3. Interactive Elements
- **Smooth Scrolling**: Enhanced navigation between sections
- **Demo Animations**: Interactive responses with fade-in effects
- **CTA Buttons**: Strategic call-to-action placement for engagement

## Data Flow

### Static Content Delivery
1. User requests website
2. Python HTTP server serves static files
3. Browser loads HTML, CSS, and JavaScript
4. Interactive elements initialize on page load

### User Interaction Flow
1. Users land on hero section
2. Navigation allows jumping to specific sections
3. CTA buttons guide users through learning journey
4. Interactive demonstrations provide hands-on experience

## External Dependencies

### CDN Resources
- **Tailwind CSS**: `https://cdn.tailwindcss.com` - Utility-first CSS framework
- **Google Fonts**: Poppins font family for typography
- **Font Awesome**: `https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css` - Icon library

### Development Tools
- **Python HTTP Server**: Built-in development server (port 5000)
- **Replit Environment**: HTML and Python modules enabled

## Deployment Strategy

### Development Environment
- **Replit Platform**: Browser-based development with instant preview
- **Python HTTP Server**: Simple static file serving on port 5000
- **Hot Reload**: Automatic refresh during development

### Production Considerations
- **Static Hosting**: Can be deployed to any static hosting service
- **CDN Integration**: External resources loaded from CDNs for performance
- **Mobile Optimization**: Designed for low-bandwidth rural internet connections

### Scalability Approach
- **Static Nature**: Easy to scale with CDN distribution
- **Minimal Dependencies**: Reduces failure points and maintenance overhead
- **Progressive Enhancement**: Core content accessible without JavaScript

## User Preferences

Preferred communication style: Simple, everyday language.

## Changelog

Changelog:
- June 27, 2025. Initial setup