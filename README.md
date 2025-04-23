# Save Our Oceans - Sustainable UX Campaign

This project is a sustainable UX campaign site focused on ocean conservation, created for the UX_H2 assignment. The campaign takes the perspective of the ocean as a non-human persona and demonstrates both sustainable design principles and deceptive UX patterns (in the dark version).

## Project Structure

- `index.html` - The main sustainable campaign site
- `style.css` - Optimized CSS for both versions of the site
- `dark-patterns.html` - The "dark UX" version with deceptive patterns
- `README.md` - This documentation file
- `accessibility-testing.md` - Template for accessibility testing documentation
- `sustainable-ux-canvas.md` - Template for the Sustainable UX Canvas

## Part 1: CO₂ & Environmental Sustainability

### Sustainable Design Principles Implemented

#### CO₂ Optimization
- **Dark theme by default** to reduce energy consumption on OLED/AMOLED screens
- **System fonts** instead of custom web fonts
- **SVG icons** instead of image files (smaller file size, scalable)
- **Minimal JavaScript** with no external libraries
- **Optimized CSS** with efficient selectors and minimal nesting
- **Single CSS file** to reduce HTTP requests
- **Cache control** meta tags
- **Preloading** critical CSS

#### The Visible Impact
- **Dark mode** to reduce power consumption on modern displays
- **Minimalist design** with a focus on typography and whitespace
- **SVG graphics** instead of heavy images
- **Semantic HTML** for better accessibility and SEO
- **Responsive design** that works well across all devices
- **Limited color palette** to reduce rendering complexity

#### The Invisible Impact
- **Minimal DOM elements** to reduce memory usage
- **Efficient JavaScript** with event delegation
- **No third-party scripts** or tracking
- **Reduced HTTP requests** by using inline SVGs
- **Semantic HTML** for better parsing efficiency
- **Theme preference storage** in localStorage to maintain user preferences

#### Non-Human Persona Integration
The campaign site is designed from the perspective of the ocean, with:
- Direct quotes from the ocean's perspective
- User stories translated into site sections
- Visual elements that represent ocean waves
- Content that addresses the ocean's challenges and needs

## Part 2: Sustainability (Social, Ethics, Accessibility)

### New Persona with Accessibility Needs

**Persona: Alex, 42, Screen Reader User with Visual Impairment**

- **Background**: Environmental scientist who relies on screen readers to navigate websites
- **Challenges**: Cannot see images or visual cues, relies on keyboard navigation and proper semantic structure
- **Needs**: Clear headings, proper alt text, logical tab order, and form labels
- **Goals**: Wants to stay informed about environmental issues and contribute to ocean conservation efforts

### Accessibility Features Implemented

- **Semantic HTML** structure with proper heading hierarchy
- **ARIA labels** for interactive elements
- **Alt text** for all images and SVGs
- **Keyboard navigation** support
- **Focus styles** for interactive elements
- **Color contrast** that meets WCAG standards
- **Responsive design** for all screen sizes
- **Form validation** with clear error messages
- **Skip to content** link (hidden until focused)
- **Reduced motion** media query support
- **Dark/light theme toggle** with clear visual indication

### Ethical Form Design

- **Clear labels** for all form fields
- **Minimal required fields** (only what's necessary)
- **Clear error messages** that explain how to fix issues
- **Transparent data usage** explanation
- **Accessible checkbox** for consent
- **Logical tab order** for keyboard navigation

## Part 3: Deceptive Patterns (Dark UX)

### Implemented Deceptive Patterns

#### Group 1: Artificial Urgency & Scarcity
- **Countdown timer** suggesting a false deadline
- **Limited availability** messages ("Only 3 spots remaining!")
- **Urgent language** throughout the site
- **Visual cues** like pulsing buttons and alert colors

#### Group 2: Manipulated Choices & Hidden Information
- **Pre-selected options** in the donation form
- **Hidden costs** in small print below form fields
- **Default opt-in** for marketing communications
- **Guilt-inducing decline options** ("No thanks, I don't care about the oceans")

#### Group 3: Obstruction & Forced Action
- **Exit-intent popup** to prevent leaving the site
- **Required phone number** collection
- **Social proof notifications** creating FOMO (Fear Of Missing Out)
- **Emotionally manipulative language** throughout

## Dark Theme Implementation

### Energy Efficiency Benefits

- **Reduced power consumption**: Dark themes can reduce battery usage by up to 30% on OLED/AMOLED displays
- **Lower eye strain**: Especially beneficial in low-light environments
- **Aligned with ocean theme**: Dark blues and blacks naturally represent the deep ocean

### Implementation Details

- **Default dark mode**: Site loads in dark mode by default for maximum energy savings
- **User preference**: Theme choice is saved in localStorage
- **Toggle button**: Easy switching between light and dark modes
- **Optimized contrast**: All text and interactive elements maintain proper contrast ratios in both themes
- **Consistent experience**: All functionality works identically in both themes

## Part 4: Testing & Documentation

### Accessibility Testing

See `accessibility-testing.md` for a template to document your accessibility testing results.

### Sustainable UX Canvas

See `sustainable-ux-canvas.md` for a template to document your sustainable UX decisions.

## Presentation Outline

### 1. Introduction (2 minutes)
- Brief overview of the campaign: "Save Our Oceans"
- Introduction to the non-human persona: The Ocean
- The problem we're addressing: plastic pollution, overfishing, climate change

### 2. Sustainable UX Model (3 minutes)
- Overview of our sustainable UX approach
- Key decisions made to reduce environmental impact
- Focus on dark theme implementation and energy savings
- Balance between aesthetics and sustainability

### 3. CO₂ Optimization (2 minutes)
- Show Digital Beacon/Ecograder results
- Highlight key optimizations made
- Before/after comparison if possible

### 4. Accessibility Testing (3 minutes)
- Introduce our accessibility persona: Alex
- Show testing results and screenshots
- Highlight key accessibility features implemented

### 5. Inclusive Design (2 minutes)
- Responsive design across devices
- Ethical form design principles
- Accommodations for various user needs

### 6. Dark UX Version (3 minutes)
- Contrast between sustainable and dark versions
- Demonstration of deceptive patterns implemented
- Ethical implications of these patterns

### 7. Conclusion (1 minute)
- Lessons learned
- Future improvements
- Q&A

## How to Use This Project

1. Open `index.html` in your browser to view the sustainable version
2. Open `dark-patterns.html` to view the deceptive patterns version
3. Use the accessibility testing tools mentioned in the assignment to evaluate the site
4. Document your findings in the provided templates
5. Prepare your presentation using the outline provided

## Testing Tools

- [WAVE Web Accessibility Evaluation Tool](https://wave.webaim.org/)
- [Axe DevTools](https://www.deque.com/axe/)
- [Lighthouse](https://developers.google.com/web/tools/lighthouse)
- [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)
- [Digital Beacon](https://digitalbeacon.co/)
- [Ecograder](https://ecograder.com/)

## Credits

Created for UX_H2 assignment, focusing on sustainable UX design, accessibility, and ethical considerations.
