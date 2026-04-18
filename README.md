# 360 Café — Hi-Fi Interactive Prototype

A high-fidelity, single-file interactive website prototype for **360 Café & Crepería**, a restaurant located in Turrialba, Alajuela, Costa Rica. Built as a UX/UI portfolio case study.

**Live Demo → [https://mauzunigacr.github.io/360-cafe/](https://mauzunigacr.github.io/360-cafe/)**

---

## About the Project

This prototype simulates the complete customer experience for 360 Café's website, including browsing, ordering, checkout, and reservation flows. It was developed as part of an ICM Website & Tech Publishing course case study.

### Pages Included

| Page | Description |
|---|---|
| Home | Hero section, menu highlights, reservation strip |
| Menu | Full menu with 10 categories, filter pills, sub-tabs |
| Product Detail | Item view with size selector (drinks only), add to cart |
| Cart | Full cart table with quantities and totals |
| Checkout | Billing form with SINPE Mobile payment flow |
| Order Confirmation | Post-purchase confirmation screen |
| About Us | Story, photo gallery carousel, reviews, FAQ |
| Contact Us | Contact info, message form, Google Maps, hiring form |
| Reservations | Reservation request form |
| Blog | Two featured blog posts |

### Key Features

- **Bilingual** — Full English / Spanish toggle (🇬🇧 / 🇪🇸)
- **Shopping cart drawer** — Slides in from the right with live item count
- **Floating cart FAB** — Always-visible cart button
- **Auto-playing gallery carousel** — Venue photos with dot indicators
- **SINPE Mobile checkout** — Costa Rica's local mobile payment system
- **Google Maps embed** — Live map of the café location
- **Fully responsive layout** — Desktop-optimized prototype

### Tech Stack

- Pure HTML5 + CSS3 + Vanilla JavaScript (single file)
- [Poppins](https://fonts.google.com/specimen/Poppins) + [Poetsen One](https://fonts.google.com/specimen/Poetsen+One) via Google Fonts
- [Font Awesome 6](https://fontawesome.com/) for icons
- No frameworks, no build tools

---

## Project Structure

```
360-cafe/
├── index.html              # Complete prototype (HTML + CSS + JS)
├── README.md
├── .gitignore
└── assets/
    └── images/
        ├── logo.png        # 360 Café brand logo
        ├── homepage/       # Hero and reservation backgrounds
        │   └── menu-section/  # Home page menu category thumbnails
        ├── venue/          # Gallery photos (café interior)
        ├── drinks/         # Coffee and beverage photos
        ├── crepes/         # Crepe dish photos
        ├── menu/           # Food item photos (fast food, sandwiches, pastries)
        └── about/          # About Us story image
```

---

## How to Run Locally

No installation or build step needed. Just open `index.html` in any modern browser:

```bash
git clone https://github.com/your-username/360-cafe.git
cd 360-cafe
open index.html   # macOS
# or double-click index.html in your file explorer
```

## How to Deploy on GitHub Pages

1. Push this repo to GitHub
2. Go to **Settings → Pages**
3. Under *Source*, select **Deploy from a branch**
4. Choose **main** branch, **/ (root)** folder
5. Click **Save** — your site will be live at `https://your-username.github.io/360-cafe/`

---

## Credits

- **Design & UX:** Mauricio Zuniga — [github.com/mauzunigacr](https://github.com/mauzunigacr)
- **Photography:** 360 Café & Crepería, Turrialba, Costa Rica
- **Course:** ICM 505 — Website & Tech Publishing Basics

---

*© 2026 360 Café & Crepería. Prototype for educational/portfolio purposes.*
