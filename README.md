# Recommended Consumables Carousel — Global Industrial

A responsive product carousel prototype built as a front-end assignment for **Global Industrial**. It showcases a "Recommended Consumables" widget with product cards, individual add-to-cart selection, a running total price display, and an "Add All to Cart" action.

---

## Features

- **Responsive carousel** — displays 4 cards on desktop, 3 on tablet, 2 on small tablet, 1 on mobile
- **Prev / Next arrow navigation** with dot indicators
- **Touch / swipe support** for mobile devices
- **Per-card checkbox selection** — toggle individual products in/out of the cart
- **Live total price** — updates dynamically as products are selected/deselected with a scale animation
- **Add All to Cart** button — selects all products at once; transforms to a confirmation state when all are added
- **Toast notifications** — brief confirmation message on add/remove actions
- **Smooth CSS transitions** and hover effects throughout

---

## Project Structure

```
Carausel Assignment/
├── carousel-prototype.html   # Single self-contained HTML file (markup + CSS + JS)
├── README.md
└── Assets/
    └── Images/
        ├── box.jpg
        ├── gloves.jpg
        ├── helmate.jpg
        ├── plier.jpg
        ├── safety-vest.jpg
        ├── tape.jpg
        └── wrapper.jpg
```

---

## Product Catalogue (Sample Data)

| # | Product | Category | Price |
|---|---------|----------|-------|
| 1 | Heavy-Duty Corrugated Cardboard Shipping Box (Pack of 25) | Packaging & Shipping | $299.99 |
| 2 | Premium Protective Wrapping Roll, 24" × 500 ft | Packaging Supplies | $489.00 |
| 3 | Type I Safety Hard Hat, ANSI Z89.1 | Head Protection | $349.00 |
| 4 | Industrial Adhesive Tape Roll, 2" × 60 Yds | Tapes & Adhesives | $89.99 |
| 5 | 8" Combination Pliers, Drop Forged Steel | Hand Tools | $199.00 |
| 6 | ANSI Class 2 Hi-Vis Safety Vest | Safety Apparel | $149.99 |
| 7 | Heavy-Duty Waterproof Work Gloves | Hand Protection | $599.00 |
| 8 | Economy Corrugated Mailer Box, 6×6×6 in (Pack of 50) | Packaging & Shipping | $59.99 |

---

## Tech Stack

| Technology | Usage |
|------------|-------|
| HTML5 | Semantic markup |
| CSS3 | Custom properties, Flexbox, responsive media queries, transitions |
| Vanilla JavaScript (ES6+) | Carousel logic, state management, DOM rendering |
| Google Fonts | Inter (body) · Kanit (headings) |

No build tools, frameworks, or external libraries are required.

---

## Getting Started

1. Clone or download the repository.
2. Open `carousel-prototype.html` directly in any modern browser — no server required.

```bash
# Optional: serve locally with VS Code Live Server or any static server
npx serve .
```

---

## Responsive Breakpoints

| Breakpoint | Cards Visible |
|------------|--------------|
| ≥ 1200 px | 4 |
| 900 – 1199 px | 3 |
| 580 – 899 px | 2 |
| < 580 px | 1 (swipe + dots) |

---

## Design Tokens

| Token | Value | Usage |
|-------|-------|-------|
| `--primary` | `#E8612C` | Buttons, accents |
| `--secondary` | `#1A2744` | Dark UI elements |
| `--accent` | `#FFB800` | Highlight color |
| `--text` | `#1A1A2E` | Body text |
| `--max-width` | `1440px` | Page cap |

---

## Assignment Context

This prototype was created as part of a **UI/UX front-end assignment** for Global Industrial to demonstrate a production-ready carousel widget that could be embedded in a product detail or order page.
