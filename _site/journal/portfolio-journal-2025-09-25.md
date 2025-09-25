# Portfolio Journal – 2025-09-25

## Key Points & Concepts

### 1. Project Structure
- Main folders: `_layouts/`, `assets/css/`, `assets/img/`, content pages (`index.md`, etc.)

### 2. Jekyll Basics
- Markdown files + layout templates = static site
- `_config.yml` controls site settings

### 3. Homepage Hero Section
- Hero section split: text + profile image
- CSS: `.hero`, `.hero-content`, `.profile-container`, `.profile-photo`
- How to resize: change `width`/`height` in `.profile-container` in `assets/css/main.css`

### 4. Profile Image with Blurred Background
- Blurred background via CSS pseudo-element (`::before`)
- Sharp circular image on top
- Change image: replace `/assets/img/profile.jpg`

### 5. Color Harmony & Gradients
- Unified gradients for hero/profile/footer
- How to switch: edit `background` in `.hero` and `.profile-container`

### 6. Responsive Design
- Mobile layout via `@media (max-width: 768px)`
- Smaller profile image/container on mobile

### 7. Section Spacing & Font Sizes
- Reduced hero padding/font size for harmony
- Adjust spacing: change `margin` in CSS (e.g., `.page-content h2`)

### 8. Footer & Color Scheme
- Footer uses `#34495e` for consistency
- All major sections use matching gradients/colors

### 9. How to Edit & Customize
- Change colors: edit `background`/`color` in CSS
- Change image: replace `/assets/img/profile.jpg`
- Change sizes: edit `width`/`height` in CSS
- Adjust spacing: edit `padding`/`margin` in CSS

### 10. Improvements Made
- Unified color scheme
- Blurred image background
- Responsive design
- Easy-to-edit CSS
- Clear separation of content/style

---

## Journal Continuation Plan
- Each session, add a new entry in this folder (e.g., `portfolio-journal-YYYY-MM-DD.md`)
- Use clear section headings for each new concept or change
- Summarize what was learned, why changes were made, and how to edit in the future
- This folder is excluded from publishing (see `_config.yml` > `exclude:`)

---

**Next Steps:**
- Continue adding journal entries for each new feature, design, or learning point
- Use this as your private learning log and reference
- Ask for more explanations or code samples as needed

---

*This journal is private and will not be published on your portfolio site.*
