# AURA & ÉLIXIR — Maison de Haute Parfumerie Paris

A luxury e-commerce and brand website for an artisanal fragrance house built with modern **HTML5**, **CSS3**, and **Vanilla JavaScript**.

---

## 🌟 Key Features

1. **Editorial Luxury Aesthetic**
   - Obsidian midnight palette with warm gold leaf gradients and champagne accents.
   - Glassmorphic navigation header with dynamic scroll elevation.
   - Distinctive typography using Google Fonts: *Cinzel* (Monogram & Branding), *Cormorant Garamond* (Serif Editorial Titles), and *Plus Jakarta Sans* (Modern Clean UI).

2. **Interactive Olfactory Catalog & Filtering**
   - 8 bespoke luxury fragrances with high-resolution imagery and distinct scent profiles.
   - Category filtering (*All, Woody & Oud, Floral & Rose, Amber & Spice, Fresh Citrus*).
   - Real-time instant search by perfume name, subtitle, category, or olfactory notes.
   - Sorting by *Featured*, *Price: Low to High*, *Price: High to Low*, and *Highest Rated*.
   - Dynamic bottle volume switchers (**30ml**, **50ml**, **100ml**) with real-time price updates per card.

3. **Interactive Scent Profiler Quiz ("Find Your Signature Scent")**
   - A 3-step intuitive fragrance consultation questionnaire matching persona, scent family, and occasion.
   - Dynamic matching algorithm that calculates and presents the user's bespoke harmony match with a direct "Add to Bag" and "View Full Notes" option.
   - Retake option to explore alternate profiles.

4. **Detailed Quick View Modal**
   - Full scent pyramid breakdown: **Top Notes (Head)**, **Heart Notes (Cœur)**, and **Base Notes (Fond)**.
   - Sillage and longevity indicators (e.g. *14+ Hours*, *Enveloping*).
   - Interactive flacon size selector and quantity input with instant bag addition.

5. **Slide-Out Shopping Bag Drawer**
   - Slide-out drawer with backdrop blur.
   - Quantity increment/decrement and item removal.
   - **Free Shipping Progress Tracker**: dynamically indicates how much is left to unlock free shipping ($200 threshold).
   - **Promo Code System**: enter **`LUMIERE15`** for an instant 15% discount calculation.
   - Persistent bag storage using `localStorage` so items remain after refreshing.

6. **Interactive Private Wishlist**
   - Click the heart icon on any flacon to save or remove from your private wishlist.
   - Dedicated slide-out drawer with "Move to Bag" capability.
   - Wishlist count badge synchronization.

7. **Mock Checkout Simulator**
   - Multi-step modal with customer details, shipping address, and simulated payment methods (Card, Apple Pay, PayPal).
   - Generates unique bespoke Order Confirmation with animated checkmark screen and unique Order ID (e.g. `ORDER #AE-829143`).

8. **Educational & Storytelling Sections**
   - **The Craft / Grasse Heritage**: Story of 60-day slow maceration, natural absolutes, and French glass flacons.
   - **The Anatomy of an Extrait**: Educational three-movement breakdown of perfume evolution on skin.
   - **Press Accolades & Connoisseur Reviews**: Vogue, GQ, and verified buyer reviews.
   - **VIP Circle Newsletter Signup**: Newsletter subscription with instant notification.
   - **Toast Notifications**: Sleek floating notifications for cart additions, wishlist updates, promo codes, and orders.

---

## 📁 File Structure

```text
e:\New folder\New folder (3)\
│
├── index.html            # Main semantic HTML structure & modal templates
├── README.md             # Project documentation & guide
│
├── css\
│   └── style.css         # Complete luxury dark-gold styling, grid/flexbox, animations
│
└── js\
    ├── products.js       # Fragrance catalog database & scent profiler quiz questions
    └── app.js            # App state, cart/wishlist management, modals, and quiz engine
```

---

## 🚀 How to Run the Website

No build tools, bundlers, or local servers are required!

1. Open your file explorer and navigate to `e:\New folder\New folder (3)\`.
2. Double-click on **`index.html`** to open it in your default web browser (Google Chrome, Microsoft Edge, Mozilla Firefox, Safari, etc.).
3. Alternatively, right-click `index.html` and select **Open with -> Google Chrome**.

---

## 💎 Test Data & Promo Codes

- **Discount Code**: Use promo code **`LUMIERE15`** in the Shopping Bag drawer to get 15% off your order!
- **Free Shipping Threshold**: Free worldwide express shipping activates on orders over **$200**.

---

## 🎨 Customizing the Website

- **Add or Edit Fragrances**: Open `js/products.js` and modify or add new objects to the `FRAGRANCES` array with custom notes, image URLs, and pricing.
- **Change Colors or Fonts**: Open `css/style.css` and adjust the variables under `:root` (e.g. `--gold-primary`, `--bg-primary`, `--font-serif`).
