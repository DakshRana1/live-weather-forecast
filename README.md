# 🌤️ Atmos – Weather Dashboard

A modern, responsive weather dashboard built with React, TypeScript, and Vite. Atmos provides an intuitive interface for visualizing weather data with smooth animations and clean design.

---

## ✨ Features

- 📊 Interactive weather charts powered by Chart.js
- 💨 Real-time weather data visualization
- 🎨 Responsive UI with Tailwind CSS
- 🔄 Smooth transitions using Framer Motion
- 🧭 Multi-page navigation with React Router
- 🔍 Element inspector for development (Alt+Shift+I)

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Framework | React 19 + TypeScript |
| Build Tool | Vite 7 |
| Styling | Tailwind CSS 4 |
| Charts | Chart.js + react-chartjs-2 |
| Animations | Framer Motion |
| Routing | React Router DOM 7 |
| Icons | Lucide React |
| Linting | ESLint + typescript-eslint |

---

## 🚀 Getting Started

### Prerequisites

- Node.js 18+
- npm or yarn

### Installation

```bash
# Clone the repository
git clone https://github.com/your-username/atmos-weather-dashboard.git
cd atmos-weather-dashboard

# Install dependencies
npm install
```

### Development

```bash
npm run dev
```

Open [http://localhost:5173](http://localhost:5173) in your browser.

### Build for Production

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

### Lint

```bash
npm run lint
```

---

## 📁 Project Structure

```
atmos/
├── public/
│   └── favicon.svg
├── src/
│   ├── main.tsx          # App entry point
│   └── ...               # Components, pages, hooks
├── index.html
├── vite.config.ts
├── tailwind.config.ts
├── tsconfig.json
└── package.json
```

---

## ⚙️ Configuration

Environment variables should be prefixed with `VITE_` or `NEXT_PUBLIC_`:

```env
VITE_WEATHER_API_KEY=your_api_key_here
```

---

## 🧑‍💻 Development Tools

This project includes a built-in **element picker** for inspecting DOM elements and tracing them back to their source files. Press `Alt+Shift+I` to toggle inspect mode during development.

---

## 📜 License

This project is private. All rights reserved.
