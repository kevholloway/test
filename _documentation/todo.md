# Todo List: Personal Bio Page

## Phase 1: Project Setup

- [ ] Create project directory structure
  - [ ] Create `styles/` directory
  - [ ] Create `assets/images/` directory
- [ ] Set up `index.html` with basic HTML5 structure
- [ ] Create `styles/main.css` file
- [ ] Add viewport meta tag for mobile responsiveness

## Phase 2: HTML Structure

- [ ] Create main container with centered layout
- [ ] Build Profile Section
  - [ ] Add circular image container (placeholder or CSS-based)
  - [ ] Add H1 heading for name
  - [ ] Add descriptive alt text for profile image
- [ ] Build About Me Section
  - [ ] Add paragraph element with descriptive text
- [ ] Build Social Links Section
  - [ ] Create container for social buttons
  - [ ] Add Twitter/X button with link (target="_blank", rel="noopener noreferrer")
  - [ ] Add GitHub button with link (target="_blank", rel="noopener noreferrer")
- [ ] Build Hire Me Section
  - [ ] Add button with `mailto:` link and pre-filled subject line
- [ ] Add semantic HTML elements (proper heading hierarchy)
- [ ] Add meta tags (title, description, Open Graph tags)
- [ ] Add optional JSON-LD structured data for Person schema

## Phase 3: CSS Styling - Base Styles

- [ ] Add CSS reset/normalize for cross-browser consistency
- [ ] Set up CSS custom properties (variables) for theme management
- [ ] Implement dark mode color scheme
  - [ ] Dark background color (#0d1117, #161b22, or #1a1a1a)
  - [ ] Light text color (#ffffff, #e6edf3, or #f5f5f5)
  - [ ] Accent colors for buttons/links
- [ ] Set up typography
  - [ ] Large, bold headings (2.5rem - 4rem desktop, 2rem - 3rem mobile)
  - [ ] Readable body text (1rem - 1.25rem)
  - [ ] Font weights: 700 for headings, 400 for body
  - [ ] Font family: System font stack or web font (Inter, Roboto, or system-ui)
  - [ ] Appropriate line-height values
  - [ ] Use `font-display: swap` if using web fonts

## Phase 4: CSS Layout & Components

- [ ] Implement centered layout
  - [ ] Max-width container (800px - 1200px)
  - [ ] Center using Flexbox or CSS Grid
  - [ ] Optional: Vertical centering with min-height: 100vh
- [ ] Style Profile Section
  - [ ] Circular image using `border-radius: 50%`
  - [ ] Optional: Hover effect or subtle animation
- [ ] Style Social Link Buttons
  - [ ] Hover states with color transitions
  - [ ] Minimum 44x44px touch targets
- [ ] Style Hire Me Button
  - [ ] Prominent styling to draw attention
  - [ ] Minimum 44x44px touch target
- [ ] Ensure all interactive elements are keyboard accessible

## Phase 5: Responsive Design

- [ ] Implement mobile-first approach
- [ ] Add media queries for breakpoints (320px, 768px, 1024px)
- [ ] Make images flexible (`max-width: 100%`, `height: auto`)
- [ ] Adjust spacing for mobile (1rem - 2rem padding/margin)
- [ ] Test vertical stacking on mobile
- [ ] Ensure touch targets meet minimum size requirements

## Phase 6: Accessibility

- [ ] Verify semantic HTML structure
- [ ] Add descriptive alt text to profile image
- [ ] Add ARIA labels where needed
- [ ] Test keyboard navigation for all interactive elements
- [ ] Verify color contrast meets WCAG AA standards
  - [ ] 4.5:1 for normal text
  - [ ] 3:1 for large text

## Phase 7: Testing & Optimization

- [ ] Test on multiple devices (mobile, tablet, desktop)
- [ ] Test on multiple browsers (Chrome, Firefox, Safari, Edge)
- [ ] Test last 2 versions of major browsers
- [ ] Optimize profile image (compress, use WebP with fallback)
- [ ] Validate HTML (W3C validator)
- [ ] Validate CSS (W3C validator)
- [ ] Test performance and loading times
- [ ] Verify graceful degradation for older browsers

## Phase 8: Polish & Final Checks

- [ ] Review all features against product requirements
  - [ ] Profile Section with circular photo and name ✓
  - [ ] About Me paragraph ✓
  - [ ] Social Links (Twitter/X, GitHub) ✓
  - [ ] Hire Me button with email link ✓
  - [ ] Dark mode by default ✓
  - [ ] Large, bold typography ✓
  - [ ] Mobile friendly ✓
  - [ ] Centered layout ✓
- [ ] Code review and cleanup
- [ ] Final visual review
- [ ] Documentation review

## Optional Future Enhancements

- [ ] Light/dark mode toggle
- [ ] Smooth scroll animations
- [ ] Loading states
- [ ] Analytics integration
- [ ] Contact form (instead of mailto)
- [ ] Blog section
- [ ] Portfolio/projects showcase
- [ ] Multi-language support

- [ ] Update Twitter link to https://x.com/adamandkev
- [ ] Update GitHub link to https://github.com/adamandkev
- [ ] Change "Hire Me" button text to "Contact" and make it open mailto:kev@adamandkev.com
- [ ] Add a new Instagram button linking to https://instagram.com/adamandkev

