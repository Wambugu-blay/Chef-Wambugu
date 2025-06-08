# Chapter & Sip – Styles Overview

## Color System

**Palette:**
- **Parchment (`#f9e6d0`)**: Used as the main background for a warm, inviting feel.
- **Espresso (`#3A2E24`)**: Primary text color for strong contrast and readability.
- **Latte (`#D8C3A5`)**: Accent and hover color for subtle highlights.
- **Sage (`#8A9B68`)**: Secondary accent for calming, organic touches.
- **Terracotta (`#E07A5F`)**: Used for links and interactive elements to draw attention.

**Rationale:**  
The palette is inspired by cozy coffeehouse and bookshop tones, aiming for warmth, comfort, and readability. Each color is assigned to maximize contrast and accessibility while maintaining a cohesive, inviting aesthetic.

---

## Breakpoint Logic

- **Mobile (default):**  
  Single-column layout for simplicity and readability.
- **Medium screens (`md:`):**  
  Switches to a two-column grid for book cards and content, making better use of horizontal space.
- **Large screens (`lg:` and up):**  
  Expands to three or more columns, providing a denser, more immersive browsing experience.

*Note: Breakpoints are managed via Tailwind’s responsive utilities in the HTML, not directly in the CSS file.*

---

## Creative Divergence from the Mockup

- **Typography:**  
  Used a refined serif (`Cormorant Garamond`) for headings and a modern sans-serif (`Open Sans`) for body text, enhancing the literary and contemporary feel.
- **Book Card Animation:**  
  Added a 3D hover effect (`rotateY` and shadow) to book covers for a tactile, interactive experience.
- **Navigation Links:**  
  Introduced an animated underline on hover for navigation links, improving feedback and polish.
- **Utility-First Approach:**  
  Leveraged Tailwind CSS for rapid prototyping and consistent spacing, diverging from static mockup spacing.
- **Custom Utilities:**  
  Created custom color and font utilities for easy reuse and maintainability.

---

*This approach ensures the site feels both familiar and fresh, balancing usability with a unique, bookish charm.*