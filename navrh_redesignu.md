# Redesign of www.tomashajek.cz

This plan outlines the approach to redesigning the personal website of Tomáš Hájek. Based on the current content of the site, it serves as a portfolio and informational hub about his work as a lecturer, photographer, Canva graphics expert, and LEGO Education trainer.

The new design will focus on a modern, premium aesthetic with smooth micro-animations, clear typography, and a dynamic user experience.

## User Review Required

> [!IMPORTANT]
> Please review the open questions below to guide the technical and visual direction before I begin execution.

## Open Questions

> [!WARNING]
> 1. **Technology Stack**: I plan to build this using plain HTML, Vanilla CSS, and JavaScript for maximum performance and control over animations. Would you prefer using a framework like React (Vite) or Next.js instead?
> 2. **Design & Aesthetics**: Do you prefer a sleek dark mode, a clean light mode, or a specific color palette (e.g., vibrant accents)?
> 3. **Content & Media**: Since this is a portfolio, imagery is crucial. Should I use AI-generated placeholders for the initial draft, or can you provide the images you'd like to use?
> 4. **Multipage vs. Single Page**: Should we structure this as a modern Single Page Application (smooth scrolling between sections) or keep separate pages for Portfolio, Kurzy, O mně, and Kontakt?

## Proposed Changes

We will create a foundational web project in the current empty directory `/Volumes/LaCie 2025/PROJEKTY VAJB/Tom Web`.

### HTML/CSS Foundation
We will build a responsive, semantic foundation.
#### [NEW] [index.html](file:///Volumes/LaCie 2025/PROJEKTY VAJB/Tom Web/index.html)
Will contain the main structure, including:
- **Hero Section**: High-impact introduction.
- **Portfolio Section**: Galleries for photography, events, etc.
- **Courses Section**: Information about courses (social media, Canva, LEGO).
- **About Me Section**: Biography and qualifications.
- **Contact Section**: Email and phone number.

#### [NEW] [style.css](file:///Volumes/LaCie 2025/PROJEKTY VAJB/Tom Web/style.css)
Will contain all the styling, utilizing a modern design system with CSS variables, responsive layouts (Flexbox/Grid), and premium animations (e.g., glassmorphism, hover effects).

#### [NEW] [script.js](file:///Volumes/LaCie 2025/PROJEKTY VAJB/Tom Web/script.js)
Will handle interactivity, such as a sticky navigation bar, smooth scrolling, and scroll-triggered fade-in animations.

## Verification Plan

### Automated/Local Testing
- I will run a local development server to test the site across different viewport sizes (mobile, tablet, desktop).
- Verify SEO tags and semantic HTML structure.

### Manual Verification
- Provide you with the local files or a local server link to view and interact with the redesigned site on your machine.
