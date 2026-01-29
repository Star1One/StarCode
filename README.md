

# 🛒 Book Shop Website App

### It’s a “design” for learning purposes.

This project is inspired by e-commerce bookstore designs for educational purposes.

No affiliation or connection with the real company.

---
## utility-shop-app@0.1.0 dev
**Tech Stack:** Next.js v16, React v19, TypeScript 5, Tailwind CSS, JSON Server, React Hot Toast

A modern e-commerce web app for books and products, with dynamic cart, just show ratings, and user authentication.

---

### ⚡ Features

       - Product Display: Grid listing with images, title, author, narrator, and price
       - Shopping Cart: Add/remove items, adjust quantities, persist in localStorage, toast notifications
       - Authentication: Cookie-based login/logout, protected dashboard routes
       - Responsive UI: Fully responsive with Tailwind CSS
       - Ratings & Discounts: Star ratings and quantity-based discount tables
       - Theming & Performance: Custom Tailwind themes, optimized for SEO and speed
       - LocalStorage usage for cart persistence
---

### 🔸 Getting Started

#### **Prerequisites:** Node.js v20+, npm v9+

```bash
  git clone https://github.com/yourusername/utility-shop-app.git
  cd Book-Shop-App
  npm install
  npx json-server --watch _data/db.json --port 3001
  npm run dev
```

Open http://localhost:3001/home

---

### 📂 Folder Structure

```text
   src/
   ├─ app/           # Pages & server actions
   ├─ components/    # Reusable UI components
   ├─ Context/       # Cart context
   ├─ styles/        # TailwindCSS & custom styles
   └─ utils/         # Helpers (currency, backgrounds)
   public/           # Assets
```

---

### 🛠 Tech & Tools

  - Framework: Next.js v16 + React v19

  - Language: TypeScript

  - Styling: Tailwind CSS

  - State: React Context API

  - UI: React Hot Toast, React Icons, React Range

  - Pagination: react-paginate

  - Server: JSON Server (mock API)

  - Auth: Cookie-based

---

### ⚙️ Scripts

```bash
      npm run dev    # Dev server
      npm run build  # Production build
      npm run start  # Start prod server
      npm run lint   # Lint project
```

---

### 🔹 Components & Utilities

  - AddToCartStoreItems – Cart actions with toast

  - ProductItem – Product display

  - RatingDisplay – Full/half stars

  - ToastProps – Toast notifications

  - ContextProvider – Cart context functions

  - Table – Discount display

  - TickSign – UI checkmark

  - bookBackgrounds – Dynamic book gradients

  - formatCurrency – GBP formatting

  - Middleware – Protect dashboard routes

---

TailwindCSS Customization

   - Custom colors, fonts, backgrounds, and gradients for branding and books

---
#### Screenshot

