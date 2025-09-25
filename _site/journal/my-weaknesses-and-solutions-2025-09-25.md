# My Weaknesses & Solutions – 2025-09-25

## 1. CSS Layout and Sizing
**Weakness:** Unsure how to resize containers and images, and adjust spacing between sections.
**Solution:**
- To resize, change `width` and `height` in the relevant CSS class (e.g., `.profile-container`, `.profile-photo`).
- To adjust spacing, edit `margin` and `padding` properties in CSS (e.g., `.hero`, `.page-content h2`).
**Example:**
```css
.profile-container {
    width: 250px;
    height: 250px;
}
.page-content h2 {
    margin: 1.2rem 0 0.7rem 0;
}
```

## 2. CSS Gradients and Color Harmony
**Weakness:** Unsure how to create gradients that match the site’s color scheme.
**Solution:**
- Use `background: linear-gradient(...)` in CSS.
- Match gradient colors to header/footer for a unified look.
**Example:**
```css
.hero {
    background: linear-gradient(135deg, #2c3e50 0%, #34495e 100%);
}
```

## 3. Blurred Image Backgrounds
**Weakness:** Didn’t know how to create a blurred background effect for images.
**Solution:**
- Use a CSS pseudo-element (`::before`) with `filter: blur(...)` and `mix-blend-mode`.
**Example:**
```css
.profile-container::before {
    content: '';
    background-image: url('../img/profile.jpg');
    filter: blur(8px) brightness(0.4);
    mix-blend-mode: overlay;
}
```

## 4. Responsive Design
**Weakness:** Unsure how to make the site look good on mobile.
**Solution:**
- Use media queries in CSS (`@media (max-width: 768px)`) to adjust layout and sizes for smaller screens.
**Example:**
```css
@media (max-width: 768px) {
    .profile-container {
        width: 200px;
        height: 200px;
    }
}
```

## 5. Section Spacing and Font Sizes
**Weakness:** Too much space or large fonts in some sections.
**Solution:**
- Reduce `padding`, `margin`, and `font-size` in the relevant CSS classes.
**Example:**
```css
.hero {
    padding: 2.5rem 0;
}
.hero-title {
    font-size: 2.5rem;
}
```

## 6. Keeping Private Documentation
**Weakness:** Didn’t know how to keep a private journal for learning.
**Solution:**
- Create a `journal` folder and exclude it from publishing in `_config.yml`.
- Save learning logs and guides in this folder for personal reference.

---

## How to Improve
- Practice editing CSS properties and see how the site changes.
- Use comments in CSS to experiment with different styles.
- Ask for explanations and code samples for anything unclear.
- Keep adding to your journal and review past solutions.

---

*This document is your personal review of weaknesses and solutions. Use it to track your progress and become a better programmer!*