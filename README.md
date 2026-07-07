# 🍓 Freeeze — Fruit Shop Website Template

A multi-page static website for a fruit/food shop, built with pure HTML5 and CSS3.

---

## 📁 Project Structure

```
project/
├── index.html          # Home page
├── about.html          # About page
├── prouducts.html      # Products page
├── blog.html           # Blog listing page
├── singlepost.html     # Single blog post page
├── contact.html        # Contact page
├── style.css           # Global stylesheet
└── images/             # All images used across pages
    ├── logo.png
    ├── bg-home.jpg
    ├── bg-header-about.jpg
    ├── face.png
    ├── twitter.png
    ├── google.png
    ├── linked.png
    ├── kiwi.jpg
    ├── mango.jpg
    ├── cantaloupe.jpg
    ├── blackberry.jpg
    ├── strawberry.jpg
    ├── blueberry.jpg
    ├── grapes.jpg
    ├── green-apple.jpg
    ├── pineapple.jpg
    ├── new-chills.png
    ├── berries.png
    ├── on-diet.png
    └── strwberry-delights.jpg
```

---

## 📄 Pages Overview

| Page | File | Description |
|------|------|-------------|
| Home | `index.html` | Hero section, intro, social links |
| About | `about.html` | Community info, template details |
| Products | `prouducts.html` | Fruit product grid using tables |
| Blog | `blog.html` | Blog post listings with sidebar |
| Single Post | `singlepost.html` | Full blog post with recent posts sidebar |
| Contact | `contact.html` | Inquiry form + contact info |

---

## 🎨 Color Palette

| Name | Hex | Usage |
|------|-----|-------|
| Pink/Red | `#be1e5f` | Headings, accents, buttons |
| Dark Pink | `#a51450` | Social section bg, links |
| Yellow-Green | `#c3cd14` | Section backgrounds, button hover |
| Dark Gray | `#555555` | Nav, sidebar bg, body text |
| Light Gray | `#f5f5f5` | Nav background |

---

## 🧩 Key CSS Sections

- **`nav`** — Fixed-style navigation bar with inline list items
- **`.one`** — Full-viewport hero image section
- **`.sec`** — Introduction/feature section with positioned image
- **`.three`** — Yellow-green highlights section with table layout
- **`.social`** — Footer with social media icons
- **`.about`** — About page header banner
- **`.aboutContent`** — Two-column float layout (left sidebar + right content)
- **`.prod`** — Products page with table-based image grid
- **`.blog`** — Blog section header
- **`.posts`** — Blog post list with absolutely positioned sidebar
- **`.single`** — Single post layout using CSS Grid (`auto-fit`)
- **`.contact`** — Contact form with CSS Grid layout

---

## 🚀 How to Run

No build tools or dependencies needed. Just open any HTML file in your browser:

```bash
# Option 1: Open directly
open index.html

# Option 2: Use VS Code Live Server extension (recommended)
# Right-click index.html → "Open with Live Server"

# Option 3: Use a simple local server
npx serve .
# or
python3 -m http.server 3000
```

---

## ⚠️ Known Issues & Notes

- The `prouducts.html` filename has a typo (should be `products.html`) — all nav links reference the typo, so keep it consistent if you rename.
- Layout uses **floats** and **tables** for structure — no Flexbox/Grid on most pages (except `.single` and `.contact`).
- The site is **not responsive** — designed for desktop viewports only.
- The `<button class="btn">load more</button>` in `blog.html` is placed inside a `<table>` tag, which is invalid HTML — consider moving it outside.

---

## 🛠️ Technologies Used

- **HTML5** — Semantic structure
- **CSS3** — Styling, positioning, pseudo-elements
- No JavaScript, no frameworks, no build tools

---

## 📝 License

Free to use for personal and commercial projects.  
Template design by **Free Website Templates**.  
© 2023 Freeeze. All rights reserved.
