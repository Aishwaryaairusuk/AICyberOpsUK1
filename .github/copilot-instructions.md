# AI Agent Instructions for Vasave Business Solutions Website

## Project Overview
This is a business solutions website for Vasave Business Solutions showcasing various technology and consulting services. The project uses a static HTML structure with Bootstrap for styling and responsive design.

## Architecture

### Core Components
- Static HTML pages in root directory for main sections
- Service-specific pages under `/services/` directory
- Nested service categories (e.g., `/services/cyber-security/`, `/services/infrastructure/`)
- Shared assets in `/css/`, `/js/`, `/img/` directories

### Key Files and Directories
- `index.html` - Main landing page
- `/services/*.html` - Service category pages
- `/css/custom.css` - Custom styling overrides
- `/js/custom.js` - Custom JavaScript functionality
- `/img/` - Image assets organized by type (banner, icons, logo, etc.)

## Development Patterns

### HTML Structure
- Pages follow a consistent section-based layout:
  ```html
  <!-- start section -->
  <div class="section layout_padding_2">
      <div class="container">
          <div class="row">
              <!-- Content here -->
          </div>
      </div>
  </div>
  <!-- end section -->
  ```

### CSS Classes
- `layout_padding_2` - Standard section padding
- `text_align_left/center` - Text alignment utilities
- `heading_main` - Main heading styles
- `footer_blog`, `footer_menu` - Footer-specific styles

### Image Conventions
- All images include descriptive alt text
- Service images follow naming pattern: `services_[category]_[name].jpg`
- Icons stored in `/img/icons/` with descriptive names

## Integration Points
- Forms use `/form-process/` directory for handling submissions
- Social media links in footer
- External dependencies:
  - Bootstrap 
  - jQuery
  - Font Awesome
  - Custom animation libraries (animate.css, flashy.min.css)

## Content Structure
- Each service page includes:
  1. Header/banner section
  2. Service description
  3. Key features/benefits
  4. Relevant images
  5. Contact/CTA section
  6. Standard footer

## Navigation
- Main navigation in header
- Service sub-navigation through sidebar/dropdowns
- Footer links organized by category (About, Services, Contact)

## Best Practices
1. Maintain consistent section structure across pages
2. Use standard class names for layout and styling
3. Include SEO-friendly alt text for all images
4. Follow established URL structure for new services

## Critical Files for Understanding
- `index.html` - Base template structure
- `services.html` - Service listing pattern
- `css/custom.css` - Site-specific styles
- `js/custom.js` - Custom functionality