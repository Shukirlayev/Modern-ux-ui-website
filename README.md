# CodeFlow – React + Vite

This project is a minimal React + Vite setup for building modern, responsive web applications. TailwindCSS and Lucide icons are used for styling, smooth scroll, and animations.

---

## Features

- Built with **React 18**.
- **Vite** provides a fast dev server and Hot Module Replacement (HMR).
- Fully responsive design using **TailwindCSS**.
- Icon support with **Lucide-react** (navbar, footer, and UI components).
- Smooth scroll animations and hover effects.
- Responsive navbar with mobile menu toggle.
- Ready-to-use components: Features, Pricing, Testimonials, Footer.

---

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/Shukirlayev/Modern-ux-ui-website.git
cd <project-folder>
```

2. Install dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

4. Build the project for production:

```bash
npm run build
```

5. Preview the production build:

```bash
npm run preview
```

---

## Plugins & Libraries Used

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react) – provides Fast Refresh using Babel.
- TailwindCSS for utility-first styling and responsive layouts.
- Lucide-react for lightweight and customizable icons.

---

## Project Structure

```
src/
├─ components/
│  ├─ Navbar.jsx
│  ├─ Features.jsx
│  ├─ Pricing.jsx
│  ├─ Testimonials.jsx
│  └─ Footer.jsx
├─ App.jsx
├─ main.jsx
└─ index.css
```

- `components/` – all page sections and UI components.
- `App.jsx` – main layout and routing.
- `main.jsx` – React root and Vite entry point.
- `index.css` – TailwindCSS and global styles.

---

## ESLint & Code Quality

- Minimal ESLint configuration included.
- Ensures clean and consistent code, even without TypeScript.

---

## Recommendations

- For production applications, consider adding TypeScript and [`typescript-eslint`](https://typescript-eslint.io/) for type-aware linting.
- Components are modular and reusable, making future expansion easy.

---

This README provides a full overview of the CodeFlow project, its structure, and setup instructions.
