```markdown
# 📰 Magazine Layout with CSS Grid

This project demonstrates a modern magazine cover layout using **HTML** and **CSS Grid**. The design is inspired by traditional print magazine covers and is structured to meet specific layout requirements using grid areas, columns, and rows.

---

## 🎯 Objective

Build a responsive magazine layout by fulfilling all user stories and passing 100% of the layout tests.

---

## ✅ Features

- Fully responsive layout using **CSS Grid**
- Custom grid layout using `grid-template-areas`
- Clean, modern design with distinct article blocks
- Organized code with clear class naming

---

## 📂 File Structure

``

magazine-layout/
│
├── index.html           # Main HTML file
├── styles.css           # Linked stylesheet with all CSS Grid styling
└── README.md            # Project overview and usage instructions

``

---

## 💡 User Stories

- A `<main>` element with the class `magazine-cover`
- A `<header>` element inside the main with class `title`
- Four `<section>` elements with the classes:
  - `feature-article`
  - `small-article1`
  - `small-article2`
  - `cover-image`
- The `.magazine-cover` uses:
  - `display: grid`
  - `grid-template-areas` for layout structure
  - `grid-template-columns: repeat(3, 1fr)`
  - `grid-template-rows: auto 1fr 1fr`
  - `gap: 10px`
- Each class maps to a `grid-area`:
  - `.title` → `title`
  - `.feature-article` → `feature-article`
  - `.small-article1` → `small-article1`
  - `.small-article2` → `small-article2`
  - `.cover-image` → `cover-image`

---

## 🚀 Getting Started

1. Clone or download this repo.
2. Open `index.html` in any modern browser.
3. Customize styles in `styles.css` to make the layout your own.

```bash
git clone https://github.com/your-username/magazine-layout.git
cd magazine-layout
open index.html
``

---

## 📸 Preview

![Magazine Layout Preview](preview.png)
*(Include a screenshot if available)*

---

## 🛠️ Technologies Used

* HTML5
* CSS3 (CSS Grid)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).

---

```
