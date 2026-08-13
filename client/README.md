<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=200&section=header&text=REAL%20ESTATE%20FINDER%20%E2%80%94%20FRONTEND&fontSize=38&fontColor=FFD700&fontAlignY=42&desc=🎨%20React%20%2B%20Vite%20%2B%20Tailwind%20CSS%20%C2%B7%20Responsive%20UI&descAlignY=62&descColor=DCDCDC&animation=fadeIn" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&weight=700&size=18&duration=2800&pause=900&color=FFD700&center=true&vCenter=true&width=740&lines=%E2%9A%9B%EF%B8%8F+React+%2B+Vite+%C2%B7+Fast+Dev+%26+Build;%F0%9F%8E%A8+Tailwind+CSS+Utility-First+Styling;%F0%9F%94%84+Redux-Managed+User+%26+Theme+State;%F0%9F%93%B1+Modern%2C+Responsive+UI)](https://git.io/typing-svg)

<br/>

<p align="center">
  <a href="https://react.dev/">
    <img src="https://img.shields.io/badge/Frontend-React-61DAFB?style=for-the-badge&logo=react&logoColor=000"/>
  </a>
  <a href="https://nodejs.org/">
    <img src="https://img.shields.io/badge/Runtime-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white"/>
  </a>
  <a href="https://vitejs.dev/">
    <img src="https://img.shields.io/badge/Vite-Build_Tool-646CFF?style=for-the-badge&logo=vite&logoColor=white"/>
  </a>
  <a href="https://tailwindcss.com/">
    <img src="https://img.shields.io/badge/Tailwind_CSS-Styling-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white"/>
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge"/>
  </a>
</p>

<p align="center">
  <a href="https://github.com/NietoDeveloper/RealEstateFinder/tree/main/client">
    <img src="https://img.shields.io/badge/📂_Source-NietoDeveloper%2FRealEstateFinder%2Fclient-000000?style=for-the-badge&logo=github&logoColor=FFD700"/>
  </a>
</p>

</div>

---

## 📋 Project Overview

This is the frontend of **Real Estate Finder**, built with **React**, **Node.js**, **Vite**, and **Tailwind CSS**. It provides a modern, responsive user interface with fast development and build times.

---

## 🗂️ Project Structure

```text
client/
├── public/            # Static assets served directly
└── src/
    ├── assets/          # Static files (images, fonts, etc.)
    ├── components/       # Reusable React components
    ├── pages/             # Page-level components
    └── redux/             # Global state management
        ├── theme/           # Theme state slice
        └── user/             # User state slice
```

---

## 🔄 App Data Flow

```mermaid
flowchart LR
    A([👤 User]) -->|Interacts| B[Pages]
    B --> C[Components]
    C -->|Dispatch| D[Redux Store]
    D -->|user| E[User Slice]
    D -->|theme| F[Theme Slice]
    C -->|API Call| G([🔗 Backend API])

    style A fill:#FFD700,color:#000,stroke:#FFD700
    style D fill:#06B6D4,color:#000,stroke:#06B6D4
    style G fill:#000,color:#FFD700,stroke:#FFD700
```

---

## 🛠️ Tech Stack

<div align="center">

| Technology | Role |
|:-----------|:-----|
| **React** | JavaScript library for building user interfaces |
| **Node.js** | Runtime for development and build processes |
| **Vite** | Fast build tool and development server |
| **Tailwind CSS** | Utility-first CSS framework for styling |

</div>

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Setup Instructions

**Step 1 — Clone the repository**

```bash
git clone https://github.com/NietoDeveloper/RealEstateFinder
cd RealEstateFinder/client
```

**Step 2 — Install dependencies**

```bash
npm install
```

**Step 3 — Start the development server**

```bash
npm run dev
```

The app will be available at `http://localhost:5173`.

---

## 📦 Build Instructions

To create a production build:

```bash
npm run build
```

Output will be in the `dist` folder.

---

## 📜 Scripts

| Command | Description |
|:--------|:-------------|
| `npm run dev` | Starts the development server |
| `npm run build` | Builds the app for production |
| `npm run preview` | Previews the production build locally |

---

## 🎨 Tailwind CSS Usage

- Tailwind is configured in `tailwind.config.js`.
- Apply styles using utility classes directly in JSX.
- Custom styles can be added in `src/styles/tailwind.css`.

---

## 🧑‍💻 Development Notes

- Use JSX for React components.
- Avoid `<form>` `onSubmit` due to sandbox restrictions; use button event handlers instead.
- Use `className` instead of `class` in JSX for Tailwind classes.
- Ensure components are reusable and modular.

---

## ▶️ Running the App

- **Development:** `npm run dev` for hot-reloading.
- **Production:** Serve the `dist` folder using a static server (e.g., `npm run preview`).

---

## 👨‍💻 Author

**Manuel Nieto** — Software Developer
GitHub: [@NietoDeveloper](https://github.com/NietoDeveloper)

---

## 📄 License

This project is licensed under the **MIT License**.

<div align="center">

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=120&section=footer&animation=fadeIn" width="100%"/>

</div>
