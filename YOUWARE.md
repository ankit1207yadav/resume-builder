# Resume Builder Project

## Project Architecture
- **Single-page application** built with vanilla HTML, CSS, and JavaScript
- **Two-column layout**: Form input on left, live preview on right
- **Template system**: Four built-in templates (Professional, Modern, Minimal, Creative)
- **Dynamic sections**: Work experience and education can be added/removed dynamically
- **Real-time preview**: Updates instantly as user types

## Key Features
- Personal information input (name, email, phone, location)
- Professional summary section
- Dynamic work experience entries
- Dynamic education entries  
- Skills input with tag-based display
- Four customizable resume templates
- Print functionality with optimized styling
- PDF export guidance (browser-based)

## Code Structure
- **CSS Variables**: Consistent color scheme using CSS custom properties
- **Responsive Design**: Grid layout that adapts to mobile screens
- **Event-driven Updates**: All form inputs trigger real-time preview updates
- **Template Switching**: Visual themes applied via JavaScript style manipulation
- **Print Optimization**: Separate print styles for clean resume output

## Template System
- **Professional**: Clean black/white design with traditional formatting
- **Modern**: Gradient background with contemporary styling  
- **Minimal**: Borderless, simple layout
- **Creative**: Colorful border with modern accents

## Development Notes
- No external dependencies - pure vanilla JavaScript
- Mobile-responsive design with CSS Grid
- Form validation handled through HTML5 attributes
- Print functionality uses browser's native print-to-PDF capability