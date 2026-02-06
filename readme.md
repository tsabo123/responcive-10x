[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/N8dJ6mCd)
Figma link: https://www.figma.com/design/uEanW0qUCb9xPha544sb5e/Untitled?node-id=0-1&t=JB8eA30CD3aTtnSU-1

1. Project Setup

Create a new project directory named responsive-portfolio
Initialize the following file structure:

  responsive-portfolio/
  ├── index.html
  ├── css/
  │   └── styles.css
  └── assets/
      └── images/

Ensure all images from the design mockups are placed in the assets/images/ folder


2. Building the Foundation (HTML)

Write semantic HTML5 markup that accurately represents the content hierarchy
Use appropriate tags: <header>, <nav>, <main>, <section>, <article>, <footer>, etc.
Ensure all text content matches the design specifications exactly
Add alt attributes to all images for accessibility
Include proper meta tags in the <head> for responsive behavior:

html  <meta name="viewport" content="width=device-width, initial-scale=1.0">

3. Implementing Mobile-First CSS

Start by styling for the 375px mobile layout first
Use relative units (rem, em, %, vw, vh) instead of fixed pixels wherever possible (option)
Match all spacing, typography, colors, and layout exactly as shown in the mobile design
Pay close attention to:

Font sizes and line heights
Padding and margins
Element dimensions
Color values (use exact hex/rgb values from the design)




4. Creating Breakpoints & Desktop Layout

The mobile design should persist up to 768px
At 768px and above, transition to the desktop layout
Use CSS media queries to handle breakpoint transitions:

css  @media (min-width: 768px) {
    /* Desktop styles here */
  }
```
- Ensure smooth visual transitions between breakpoints (no layout "jumps" or broken spacing)
- Test at intermediate resolutions: 480px, 768px, 991px, 1200px, 1440px, and 1920px

---

### **5. Precision & Polish**

- **Match element dimensions exactly**—use browser DevTools to measure against design mockups
- Ensure consistent spacing between sections and components
- Verify that text doesn't overflow containers at any breakpoint
- Check that images scale proportionally and maintain their aspect ratios
- Validate that all interactive elements (links, buttons) have proper hover states if shown in the design

---

### **6. Cross-Browser & Responsive Testing**

- Test your page in at least two modern browsers (Chrome, Firefox, Safari, or Edge)
- Use browser DevTools to simulate various device sizes
- Ensure the layout doesn't break at any width between 375px and 1920px
- Verify that horizontal scrolling is never required

---

## ✅ Acceptance Criteria

Your submission will be evaluated based on the following:

- [ ] HTML is semantic, clean, and properly structured
- [ ] Mobile-First approach is correctly implemented
- [ ] Mobile design (375px) is pixel-perfect
- [ ] Desktop design (1920px) is pixel-perfect
- [ ] Layout remains intact and visually consistent at all breakpoints (375px - 1920px)
- [ ] Mobile layout is maintained up to 768px, then switches to desktop
- [ ] No horizontal scroll bars appear at any resolution
- [ ] All spacing, typography, and colors match the design specifications
- [ ] Images are properly optimized and responsive
- [ ] Code is clean, well-commented, and follows best practices
- [ ] The page is accessible (proper semantic HTML, alt texts, etc.)

---

## 📤 Submission

1. **Push your code to GitHub
2. **Submit the repository link** via the course platform
3. **Include a README.md** with:
   - Brief description of the project
   - Technologies used (HTML5, CSS3)
   - Any challenges you faced and how you solved them

**Deadline:** 02.08.2026

Good luck, Architect! Build with precision and pride. 🚀
