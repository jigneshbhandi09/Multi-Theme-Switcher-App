# 🌗 Multi-Theme Switcher App

A fully responsive and modern React application that allows users to switch between multiple themes with dynamic layout, fonts, and structure updates — built using React, TypeScript, Tailwind CSS, and Vite.

Live Demo
🔗 [Click here to view the live app](https://multi-theme-switcher-app-h4mn.vercel.app/)

🛠 Tech Stack

-  React (with Hooks + Functional Components)
-  Context API (for global theme management)
-  Tailwind CSS (utility-first styling)
-  TypeScript (for better type safety)
-  Vite (fast build tool)
- Vercel (for deployment)

📂 Folder Structure
multi-theme-switcher/<br>
├── public/
├── src/
│ ├── components/
│ │ ├── Header.tsx
│ │ ├── Footer.tsx
│ │ ├── ThemeToggle.tsx
│ │ ├── ProductList.tsx
│ │ └── ...
│ ├── context/
│ │ └── ThemeContext.tsx
│ ├── App.tsx
│ └── main.tsx
├── tailwind.config.cjs
├── postcss.config.cjs
├── index.html
├── package.json
└── vite.config.ts

Features:
- Three distinct themes: Each theme changes layout, fonts, spacing, and colors.
- Theme persistence: User's selected theme is saved in `localStorage`.
- Fully responsive design: Works on desktop, tablet, and mobile.
- Smooth animated theme switching using Tailwind transitions.
- Modular folder structure: All components are reusable and organized.Features

How to Run Locally:

```bash
# Clone the repo
git clone https://github.com/jigneshbhandi09/Multi-Theme-Switcher-App.git

# Navigate into the folder
cd Multi-Theme-Switcher-App

# Install dependencies
npm install

# Start the development server
npm run dev


