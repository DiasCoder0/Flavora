# 🍴 Flavora — Food Recipe Website

A modern, responsive food recipe website built with **HTML**, **Tailwind CSS**, and **Vanilla JavaScript**. Flavora lets users discover, filter, and save delicious recipes from around the world.

---

## 📸 Preview

| Page | Description |
|---|---|
| `index.html` | Homepage with hero, categories, recipe carousel, newsletter, and about section |
| `recipe-detail.html` | Recipe detail page with ingredients, step-by-step instructions, nutrition facts, and reviews |

---

## ✨ Features

### 🔍 Search & Filter
- **Live Search** — type in the search bar and recipes filter in real-time; page auto-scrolls to the Featured Recipes section on first keystroke
- **Category Filter** — click filter tabs (All, Quick & Easy, Vegetarian, Asian, Italian, Healthy) to narrow down recipes
- **Category Cards** — clicking a category card scrolls to the recipes section and applies the filter automatically

### 🎠 Recipe Carousel
- **2-row horizontal carousel** displaying 6 cards per page (3 columns × 2 rows)
- **Infinite loop navigation** — prev/next buttons wrap around seamlessly with no blank spaces
- **Dot indicators** — click any dot to jump to a specific page
- Carousel automatically resets to page 1 after any search or filter change

### ❤️ Favorites
- Toggle the heart icon on any recipe card to save/remove it
- Favorites are **persisted in `localStorage`** — they survive page refresh
- Toast notification appears when a recipe is saved or removed

### 📱 Responsive & Navigation
- **Mobile hamburger menu** — animates into an ✕ when open, collapses on link click
- **Sticky navbar** — gains a drop shadow when the page is scrolled
- Fully responsive layout across mobile, tablet, and desktop

### ✨ Animations
- **Scroll reveal** — sections and cards fade in as they enter the viewport (IntersectionObserver)
- **Card hover** — cards lift slightly on hover with a soft shadow

### ⬆️ Back to Top
- Button appears after scrolling 400px down, smooth-scrolls back to the top

### 📄 Recipe Detail Page (`recipe-detail.html`)
- **Servings adjuster** — +/− buttons rescale all ingredient amounts automatically
- **Ingredient checklist** — check off ingredients as you prep; clear all with one click
- **Step tracker** — click a step to mark it done (turns green ✓); reset all steps at once
- **Interactive star rating** — hover and click to select a rating before submitting
- **Submit review** — new reviews appear instantly at the top of the list
- **Follow Chef** toggle with feedback toast
- **Favorite** button synced with `localStorage` (shared with homepage)

---

## 🗂️ Project Structure

```
Flavora/
├── index.html          # Homepage
├── recipe-detail.html  # Recipe detail page
├── images/             # (reserved for local assets)
└── README.md           # This file
```

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | Page structure and semantic markup |
| Tailwind CSS (CDN) | Utility-first styling and responsive layout |
| Vanilla JavaScript | All interactivity — carousel, filter, search, favorites, etc. |
| Google Fonts | Playfair Display (headings) + DM Sans (body) |
| Unsplash | Food photography via CDN URLs |

> No build tools, no npm, no dependencies to install — open the HTML files directly in a browser.

---

## 🚀 Getting Started

1. Clone or download this repository
2. Open `index.html` in any modern browser
3. No installation or server required

```bash
# If you want a local dev server (optional)
npx serve .
```

---

## 📋 Recipe Data

The site contains **20 curated recipes** across 6 categories:

| Category | Count |
|---|---|
| 🍳 Breakfast | 3 |
| 🥗 Salads | 3 |
| 🍝 Pasta | 3 |
| 🍗 Chicken | 3 |
| 🎂 Desserts | 3 |
| 🥤 Drinks | 2 |

---

## 📱 Browser Support

Works on all modern browsers — Chrome, Firefox, Safari, Edge.

---

## 👤 Author

Built as a front-end web development assignment implementing **Tailwind CSS** with interactive JavaScript features.
