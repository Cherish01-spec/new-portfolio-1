# CHERISH Portfolio V2

An immersive, animation-rich personal portfolio built with pure HTML, CSS, and JavaScript.

This project showcases a futuristic UI system with glassmorphism, 3D tilt interactions, magnetic buttons, animated canvas stars, meteor effects, project-stack storytelling, and a Formspree-powered contact workflow.

---

## Live Identity

- Developer: Cherish Kumar Satpathy
- Role Focus: Full Stack Developer
- Location Shown: Bhubaneswar, India
- Primary Theme: Cinematic sci-fi portfolio experience

---

## What This Project Delivers

- Single-page portfolio with clear sections: Home, About, Work, Contact
- High-impact hero section with glitch typography and kinetic CTA buttons
- Complex bento-grid profile system for philosophy, stack, status, and setup
- Sticky stacked project cards for storytelling while scrolling
- Interactive contact panel with orbiting social links and AJAX form submission
- Responsive behavior tuned for desktop, tablet, mobile, and small-mobile layouts
- No build tooling required: runs directly in browser

---

## Core Features

### 1) Cinematic UI and Motion Layer
- Fixed atmospheric background system with:
	- Grid texture
	- Spotlight blur gradient
	- Canvas starfield with opacity twinkle animation
	- Programmatically generated meteor shower
- Glitch-text title effect using pseudo-elements and clip-path animation
- Animated CTA styles: liquid fill, draw-outline, rotating gradient borders

### 2) Advanced Interaction Design
- Magnetic hover effect for nav and key interactive controls
- 3D tilt-card parallax interaction for about-section cards
- Scroll-based AR/VR-style rotation for selected sections (disabled on small screens)
- Cinematic burst-blink animation on footer headline

### 3) Work Showcase Architecture
- Sticky progressive project-card stack with increasing depth and hover lift
- Technology tags per project with brand color coding
- Outbound links for demos and source repositories

### 4) Contact System
- Integrated Formspree endpoint for backend-free contact handling
- Async JavaScript submission with:
	- Loading state
	- Success state
	- Error handling for API/network failures
- Typewriter status line triggered via IntersectionObserver

### 5) Responsive Engineering
- Breakpoints for:
	- <=1200px (grid restructuring)
	- <=992px (layout realignment, effects constraints)
	- <=768px (single-column adaptation)
	- <=480px (tight mobile optimization)
- Touch-safe behavior by conditionally enabling hover-only interactions

---

## Tech Stack

- HTML5 semantic structure
- CSS3 (custom properties, advanced animation, glassmorphism, responsive layouts)
- Vanilla JavaScript (DOM APIs, canvas rendering, fetch, observers)
- Font Awesome (iconography)
- Google Fonts (Space Grotesk, Syncopate)
- Formspree (form delivery backend)

---

## Project Structure

```text
new-portfolio-main/
|- index.html      # Semantic single-page layout and content sections
|- style.css       # Complete visual system, interactions, and responsive rules
|- script.js       # Runtime interactivity, animation logic, and form handling
|- AdobeExpress.png# Profile image asset used in hero section
|- README.md       # Project documentation
```

---

## How It Works (Implementation Notes)

### HTML Layer
- Uses a fixed background wrapper plus content layers for depth separation.
- Organized into four major semantic areas:
	- Hero
	- About
	- Work
	- Footer/Contact

### CSS Layer
- Centralized design tokens via root variables:
	- Background palette
	- Accent color
	- Font families
	- Glass border values
- Defines reusable interaction classes:
	- magnetic
	- tilt-card
	- draw-btn
	- cyber-btn
- Uses responsive media blocks to preserve visual identity across devices.

### JavaScript Layer
- Initializes all interactions after DOMContentLoaded.
- Handles:
	- Scroll perspective transforms
	- Magnetic movement calculations from cursor offset and element center
	- Tilt-card rotation from pointer deltas
	- Canvas-based star animation loop
	- Dynamic meteor element creation
	- Contact form async submission lifecycle
	- Footer headline blink sequence timing

---

## Run Locally

1. Clone the repository.
2. Open the project folder.
3. Launch index.html in a browser.

Optional local server (recommended for development):

```powershell
# From project root
python -m http.server 5500
```

Then open:

```text
http://localhost:5500
```

---

## Customization Guide

### Personal Details
- Update name, bio text, and contact fields in index.html.
- Replace AdobeExpress.png with your own optimized profile image.

### Contact Endpoint
- Replace the Formspree action URL in the contact form with your own endpoint.

### Projects
- Edit project-card-stack blocks to add or remove projects.
- Update demo/code links and tag stacks per project.

### Branding
- Change theme variables in style.css root block for quick restyling.

---

## Accessibility and UX Considerations

- Uses meaningful alt attributes on images.
- Uses touch-aware interaction gating for hover-only effects.
- Includes scaled viewport and responsive typography for device coverage.
- Uses visible state feedback for form submission outcomes.

Potential future upgrades:
- Add reduced-motion preference handling for animation-heavy sections.
- Improve keyboard focus styling for all interactive controls.
- Add section landmark enhancements and ARIA labels where needed.

---

## Resume-Ready Project Description

Use this directly in your resume or portfolio case study.

### Short Version (1-2 lines)
Designed and developed a futuristic, high-performance personal portfolio using HTML, CSS, and JavaScript with advanced UI motion systems, 3D interactions, and asynchronous Formspree contact integration.

### Bullet Version (ATS Friendly)
- Engineered a fully responsive single-page portfolio with advanced animation systems including canvas starfields, meteor effects, glitch typography, and interactive 3D card tilt behaviors.
- Built modular UI interaction patterns in vanilla JavaScript (magnetic controls, scroll-based perspective transforms, and observer-triggered typewriter effects) without external frontend frameworks.
- Implemented asynchronous contact form workflow with Formspree API integration, including loading, success, and error UI states for robust user feedback.
- Designed and implemented a sticky stacked project showcase to improve visual storytelling and highlight cross-domain projects in web development and computer vision.
- Optimized mobile adaptability across multiple breakpoints while selectively disabling expensive hover/3D effects on touch devices for smoother performance.

### Impact-Oriented Variant
- Created a distinctive personal brand experience through a custom visual language (glassmorphism, kinetic gradients, animated layers) that increases recruiter and client engagement compared to static portfolio layouts.

---

## Suggested GitHub Repository Topics

- portfolio
- personal-website
- html
- css
- javascript
- frontend
- responsive-design
- web-animation
- glassmorphism
- formspree

---

## License

This project is open for personal inspiration and learning.
If you plan to reuse large sections, please provide attribution.
