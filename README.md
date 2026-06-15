# Responsive Travel Card Component

A clean, modern, and fully responsive Travel UI Card built from scratch using semantic HTML5 and vanilla CSS3. This project focuses on mastering the fundamentals of the **CSS Box Model**, **Flexbox layouts**, and establishing a clean **typographic hierarchy**.

---

##  Features

- **Modern Semantic HTML:** Built using structural, accessible HTML5 elements.
- **Self-Contained Assets:** Uses local image pathways (`./image.png`) for reliable local rendering and asset management.
- **CSS Box Model Management:** Explicit control over borders, paddings, and margins using `box-sizing: border-box`.
- **Flexbox Architecture:** Utilizes CSS Flexbox layout properties for flawless element alignment and spacing.
- **Typography Hierarchy:** Clean font pairing using Google's *Inter* font, balancing font weights and color contrasts for readability.
- **Fully Responsive:** Perfectly scales down for mobile displays and up for desktop layouts.

---

##  Core Concepts Practiced

### 1. The CSS Box Model
Ensured predictable element sizing across browsers by standardizing how dimensions, padding, and borders interact:
```css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
Flexbox Spacing
Used modern gap properties instead of stacking complex top/bottom margins to achieve a clean vertical rhythm inside the content block:

CSS
.card-content {
    display: flex;
    flex-direction: column;
    gap: 16px;
}
Visual Framework & Text Contrast
Used image framing bounds (object-fit: cover) to preserve aspect ratios, alongside deliberate text color scaling (#1e293b titles vs #8a94a6 descriptions) to keep the UI elegant and modern.

Project Structure
Bash
├── index.html   # Main HTML5 structure
├── style.css    # Custom CSS styles, variables, and typography
└── image.png    # Local travel card asset photo
