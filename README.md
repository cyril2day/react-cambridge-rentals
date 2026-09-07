# Cambridge Rentals

A simple React + Vite app that lists rental properties available in Cambridge. Built for the [LinkedIn Learning](https://www.linkedin.com/learning/) React course.

## ✨ Features

- Browse rental property listings (houses, flats, and cottages)
- Each listing shows:
  - Property type with a label badge
  - Photo
  - Number of bedrooms and bathrooms
  - Floor surface area
  - Address
  - Monthly rent
  - Availability status with an availability banner
- Fully responsive layout

## 🛠️ Tech Stack

- [React](https://react.dev/) 19
- [Vite](https://vitejs.dev/)
- [lucide-react](https://lucide.dev/) icons
- ESLint for linting

## 🚀 Getting Started

### Prerequisites

- Node.js 20+
- [pnpm](https://pnpm.io/)

### Installation

```bash
pnpm install
```

### Run the development server

```bash
pnpm dev
```

Open the URL printed in the terminal (usually `http://localhost:5173`).

### Build for production

```bash
pnpm build
```

The production-ready files are output to `dist/`.

### Preview the production build

```bash
pnpm preview
```

### Lint

```bash
pnpm lint
```

## 🌐 Deployment

This project is deployed to GitHub Pages via a GitHub Actions workflow (`.github/workflows/deploy.yml`). Every push to the `master` branch triggers a build and automatic deploy.

Live site: [https://cyril2day.github.io/react-cambridge-rentals/](https://cyril2day.github.io/react-cambridge-rentals/)

The `base` path is set to `/react-cambridge-rentals/` in `vite.config.js` to match the GitHub Pages project URL.

## 📁 Project Structure

```
src/
├── App.jsx                 # Main app component
├── components/             # Reusable UI components
│   ├── Header/             # Site header with branding and contact info
│   ├── Title/              # Page title
│   ├── PropertyList/       # Grid of property cards
│   └── Footer/             # Site footer
└── data/
    └── properties.js       # Property listing data
```

## 📄 License

This project is for educational purposes (LinkedIn Learning).
