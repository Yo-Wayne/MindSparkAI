# MindSpark AI - Educational Website

## Overview

This is a multi-page professional educational website for MindSpark AI, designed to empower rural youth with AI tools and knowledge. The project is part of a student-led nonprofit initiative targeting rural school children in Taiwan, focusing on teaching them how to use AI tools effectively rather than building them. The website serves as a comprehensive platform for education, volunteer recruitment, and program promotion.

## System Architecture

### Frontend Architecture
- **Multi-Page Website**: 6 separate HTML pages with shared navigation
- **CSS Framework**: Tailwind CSS for utility-first styling
- **Typography**: Google Fonts (Poppins) for enhanced readability
- **Icons**: Heroicons SVG icons for professional appearance
- **Responsive Design**: Mobile-first approach with professional styling

### Backend Architecture
- **Simple HTTP Server**: Python's built-in HTTP server for development
- **No Database**: Static content delivery without persistent data storage
- **No Authentication**: Public access educational content

## Key Components

### 1. Website Structure
- **Multi-Page Application**: 6 HTML pages with consistent navigation
  - `index.html` - Homepage with mission and impact stats
  - `curriculum.html` - Detailed 6-module learning curriculum
  - `recommended-ai.html` - Grid of vetted AI tools with descriptions
  - `get-involved.html` - Volunteer opportunities and partnership info
  - `donate.html` - Donation tiers and alternative support options
  - `contact.html` - Contact form and FAQ section
- **Shared Navigation**: Consistent header/footer across all pages
- **Mobile-first Design**: Optimized for rural areas with limited bandwidth

### 2. Visual Design System
- **Color Palette**: 
  - Deep Blue (#2563EB) for primary elements and buttons
  - Slate Gray (#64748B) for secondary text and subheadings
  - Light Gray (#F8FAFC) for page backgrounds
  - Charcoal Gray (#1E293B) for main body text
  - Soft Indigo (#6366F1) for highlights and accents
  - White (#FFFFFF) for cards and form backgrounds
- **Typography**: Poppins font family for all text
- **Spacing**: Consistent spacing using Tailwind utilities (py-20, max-w-7xl)

### 3. Interactive Elements
- **Smooth Scrolling**: Enhanced navigation between sections
- **Form Handling**: JavaScript form validation and submission feedback
- **Mobile Menu**: Responsive navigation for mobile devices
- **Button Animations**: Hover effects with subtle transformations

## Data Flow

### Static Content Delivery
1. User requests any page
2. Python HTTP server serves static HTML files
3. Browser loads HTML, CSS, and JavaScript
4. Navigation elements initialize across all pages

### User Interaction Flow
1. Users enter through homepage or any page
2. Shared navigation allows seamless page transitions
3. Forms provide feedback and simulate submission
4. External links direct to real AI tool websites

## External Dependencies

### CDN Resources
- **Tailwind CSS**: `https://cdn.tailwindcss.com` - Utility-first CSS framework
- **Google Fonts**: Poppins font family for typography
- **Heroicons**: Inline SVG icons for professional design

### Development Tools
- **Python HTTP Server**: Built-in development server (port 5000)
- **Replit Environment**: HTML and Python modules enabled

## Page-Specific Content

### Homepage (index.html)
- Hero section with mission statement
- Complete manifesto about AI literacy vs coding
- Impact statistics (0 schools, 6 tools, 100% free)

### Curriculum (curriculum.html)
- 6-module structured learning progression
- Detailed curriculum table with tools and projects
- Learning path with time estimates

### AI Tools (recommended-ai.html)
- 7 vetted AI tools with descriptions and links
- Usage tips and best practices
- Tool categorization by use case

### Get Involved (get-involved.html)
- Teacher and school leader partnership info
- Student volunteer opportunities
- Impact messaging and application form

### Donate (donate.html)
- Tiered donation options ($10, $50, $200)
- Custom donation form
- Alternative support methods (corporate, equipment)

### Contact (contact.html)
- Comprehensive contact form
- FAQ section
- Response time and service area information

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

## Recent Changes

- July 16, 2025: Complete rebranding from "AI for Future Minds" to "MindSpark AI" across all 6 pages
- July 16, 2025: Integrated Formspree backend (https://formspree.io/f/mkgznpkd) for get-involved and contact forms
- July 16, 2025: Implemented donation functionality with email modals and custom donation amounts (contact@mindspark.org)
- July 16, 2025: Enhanced curriculum with student-friendly 6-module structure featuring specific AI tools and project examples
- July 16, 2025: Reorganized AI tools directory into two sections: Learning & Tutoring Tools (ChatGPT, Khanmigo, Socratic, NotebookLM, QuillBot, MagicSchool AI) and Coding & Machine Learning Tools (Replit Ghostwriter, Scratch + ML Extension, Google Teachable Machine, EarSketch)
- July 16, 2025: Updated all email addresses to contact@mindspark.org

## Changelog

- June 27, 2025: Initial single-page setup
- June 27, 2025: Complete redesign to professional multi-page website with new color scheme (Deep Blue/Slate Gray), 6 pages, structured curriculum, AI tools directory, and comprehensive volunteer/donation systems