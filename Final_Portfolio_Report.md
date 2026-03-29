# CSS Enhancement Report for Personal Resume Website

**Name:** Anushka Soni  
**Academic Institution:** Indian Institute of Management Bangalore (IIMB)  
**Program:** BBA in Digital Business & Entrepreneurship  
**Status:** Completed

---

## Introduction
This document outlines the professional-grade enhancements made to my personal portfolio website. The objective was to evolve a standard resume into a high-impact, premium digital identity. The transformations leverage advanced CSS3, modern layout architectures, and interactive visual storytelling to reflect my dual identity as a **Strategic Thinker** and a **National-level Athlete**.

---

## Summary of CSS Enhancements

### 1. Premium Typography & Visual Hierarchy
*   **Font Integration:**
    *   **Inter:** Used for body text and navigation, providing a crisp, modern, and high-readability feel.
    *   **Newsreader (Serif):** Integrated for headings and identity statements to convey sophistication and academic authority (IIMB brand).
*   **Curved Branding:** Implemented an **SVG-based curved path** for the "Hi, I'm Anushka" greeting, creating a unique, magazine-style organic feel that breaks the rigid rectangular grid of traditional web design.

### 2. Multi-Page Architecture & Routing
*   **Route Separation:** Successfully transitioned from a single-page layout to a structured **multi-page system** (`index.html`, `about.html`, `playground.html`).
*   **Navigation Logic:** Developed a responsive navbar with **Active State Highlighting**, allowing users to maintain orientation across different sections of my professional journey.

### 3. Hero Section V2 (Digital First Impression)
*   **Floating Collage:** Utilized absolute positioning and CSS transitions to create a "floating" effect for key project and life images.
*   **Responsive Scaling:** The hero section adapts dynamically to screen sizes, ensuring the "Strategic Thinker" identity statement remains the focal point on both mobile and desktop.

### 4. Advanced Layout Structuring
*   **CSS Grid & Flexbox:**
    *   **Playground Grid:** Used CSS Grid for the Leadership and MUN sections to create a balanced, masonry-inspired layout for project cards.
    *   **Athletics Grid:** Implemented a standard two-column grid for high-impact sports achievements.
*   **Life Collage:** A custom 9-image responsive collage with subtle tilt transformations to give a "physical scrapbook" feel to the "Life beyond the spreadsheets" section.

### 5. Interactive Elements & Micro-Animations
*   **Scroll-Triggered Fades:** Implemented an `animate-on-scroll` system using CSS `@keyframes` and the Intersection Observer API for smooth, purposeful entrance animations.
*   **Hover States:** Custom pseudo-element (`::after`) animations on links and social icons for a tactile, responsive user experience.

### 6. Branding & Color Systems
*   **CSS Variables:** Centralized the design system using root variables:
    *   **Primary Accent:** `#1c337a` (Deep Professional Blue)
    *   **Text Primary:** `#000000`
    *   **Background Secondary:** `#f7f6ec` (Paper-like off-white for depth)
*   **Consistency:** Guaranteed uniform application of these tokens across all three pages for brand integrity.

---

## Key Improvements Table

| Feature / Section | Before (Standard Resume) | After (Anushka Soni Premium Portfolio) |
| :--- | :--- | :--- |
| **Identity Presentation** | Plain text heading | SVG Curved "Hi, I'm Anushka" + Serif identity text |
| **Image Presentation** | Static squares | Tilted floating hero images & responsive collage |
| **Routing** | Single scrolling page | Multi-page structure (Home, About, Playground) |
| **Typography** | Browser default sans-serif | Newsreader (Serif) & Inter (Sans) Pairing |
| **Layout Flow** | Linear, vertical list | Dynamic Grid, Card-based systems, & Flex-alignment |
| **Interactive UX** | Standard links | Animated active states & scroll-triggered reveals |
| **Tone & Feel** | Basic Information | High-end digital brand & storytelling |

---

## Technical Details: How to View the Site
1.  **Local Execution:** Open `index.html` in any modern web browser.
2.  **Navigation:** Use the top navigation bar to toggle between the **Impact Work**, **Leadership Playground**, and **About** pages.
3.  **Responsive Check:** Resize the browser window to see the CSS Media Queries adapt the layout for mobile devices.

## Conclusion
By implementing advanced CSS techniques—including SVG masks, CSS Grid, and sophisticated font-pairing—this project has successfully transformed a static data list into a dynamic professional narrative. The result is a website that not only displays information but communicates a brand: a leader who value precision, strategy, and athletic discipline.

---

**Submitted by:**  
Anushka Soni  
IIM Bangalore | BBA-DBE  
2025-2028
