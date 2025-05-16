# Portfolio Website - Neema Maisha

A professional portfolio website showcasing web development skills, projects, and contact information.

 Live Demo
[View Live Demo](https://neemamaisha.github.io/portfolio)

Tools Used
- Frontend: HTML5, CSS3, JavaScript (ES6+)
- Icons: Font Awesome (v6.0.0)
- Maps: Google Maps Embed API
- Hosting: GitHub Pages
- Validation: W3C HTML/CSS Validator
- Design: CSS Grid, Flexbox, Media Queries

Key Features Implemented
1. Multi-Page Navigation
   - Responsive hamburger menu for mobile
   - Active page indicators
   - Smooth scroll behavior

2. Interactive Elements
   - Dark/Light mode toggle with localStorage persistence
   - Time-based dynamic greeting
   - Image map with clickable areas
   - Embedded Google Map

3. Form Handling
   - Contact form with regex validation (email/phone)
   - Survey page with radio buttons, checkboxes, and text areas
   - Client-side validation with error messages

4. Responsive Design
   - 3-column project grid (desktop) → 1-column (mobile)
   - Print-friendly CSS for resume section
   - Mobile-first approach with media queries

5. Accessibility
   - Semantic HTML5 tags
   - ARIA labels for navigation
   - Alt text for images
   - Keyboard-navigable elements

6. SEO Optimization
   - Meta descriptions and keywords
   - Author attribution
   - Semantic heading hierarchy

Challenges Faced & Solutions

1. Responsive Navigation
Challenge: Mobile menu collapse and spacing issues  
Solution:  
- Implemented CSS media queries with breakpoints
- Used JavaScript for menu toggle functionality
- Added flexbox spacing adjustments for mobile

2. Dark Mode Implementation
Challenge: Consistent theme switching across pages  
Solution:  
- Used CSS variables for color schemes
- Added localStorage to save user preference
- Created separate dark-mode CSS classes

3. Form Validation
   Challenge: Complex regex patterns for Tanzanian phone numbers  
Solution:  
- Implemented custom regex: `/(\+255|0)[67]\d{8}/`  
- Added real-time error messages with DOM manipulation
- Tested with multiple number formats (+255, 0xx, etc.)

4. Cross-Browser Compatibility
Challenge: CSS Grid inconsistencies in older browsers
Solution:  
- Added fallback flexbox layouts
- Used autoprefixer for vendor prefixes
- Limited CSS Grid to modern browser features

5. W3C Validation Errors
Challenge: Semantic HTML structure issues  
Solution:  
- Replaced divs with semantic tags (article, section)
- Fixed improper nesting of lists
- Added alt attributes to all images

6. Map Embedding
Challenge: Google Maps responsiveness  
Solution:  
- Used percentage-based iframe dimensions
- Added wrapper div with overflow:hidden
- Implemented loading="lazy" attribute

Installation
1. Clone repository:
```bash
git clone https://github.com/neemamaisha/portfolio.git
