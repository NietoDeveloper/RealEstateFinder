<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=220&section=header&text=REAL%20ESTATE%20FINDER&fontSize=54&fontColor=FFD700&fontAlignY=42&desc=🏠%20Full-Stack%20Property%20Search%20Platform%20%C2%B7%20MERN%20%2B%20Vite&descAlignY=62&descColor=DCDCDC&animation=fadeIn" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Share+Tech+Mono&weight=700&size=20&duration=2800&pause=900&color=FFD700&center=true&vCenter=true&width=760&lines=%F0%9F%8F%A1+Browse+%26+Search+Real+Estate+Listings;%E2%9A%9B%EF%B8%8F+React+%2B+Vite+%C2%B7+Tailwind+CSS;%F0%9F%94%90+Redux-Managed+User+Sessions;%F0%9F%94%8C+Decoupled+Frontend+%2B+Backend+API;%F0%9F%8F%86+%231+GitHub+Committer+in+Colombia)](https://git.io/typing-svg)

<br/>

<p align="center">
  <a href="https://github.com/NietoDeveloper">
    <img src="https://img.shields.io/badge/Engineer-Manuel%20Nieto-blue?style=for-the-badge&logo=github"/>
  </a>
  <a href="https://committers.top/colombia#NietoDeveloper">
    <img src="https://img.shields.io/badge/Committers.top-%231%20Colombia-gold?style=for-the-badge"/>
  </a>
  <a href="https://react.dev/">
    <img src="https://img.shields.io/badge/Frontend-React-61DAFB?style=for-the-badge&logo=react&logoColor=000"/>
  </a>
  <a href="https://nodejs.org/">
    <img src="https://img.shields.io/badge/Backend-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white"/>
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
  <a href="https://github.com/NietoDeveloper/RealEstateFinder">
    <img src="https://img.shields.io/badge/📂_Source-NietoDeveloper%2FRealEstateFinder-000000?style=for-the-badge&logo=github&logoColor=FFD700"/>
  </a>
</p>

</div>

---

## 📋 Overview

**Real Estate Finder** is a full-stack web application with separated frontend and backend, built using JavaScript, React, Node.js, Vite, and Tailwind CSS. Designed to let users browse and search property listings through a clean, responsive interface backed by a dedicated RESTful API.

---

## 🗂️ Project Structure

```text
RealEstateFinder/
├── api/                  # Node.js backend for API services
│   ├── controllers/       # Business logic handlers
│   ├── models/             # Database models
│   ├── routes/              # RESTful API endpoints
│   └── utils/                # Helper functions
└── client/               # React frontend built with Vite
    ├── public/
    └── src/
        ├── assets/
        ├── components/
        ├── pages/
        └── redux/
            ├── theme/
            └── user/
```

---

## 🔄 Property Search Flow

```mermaid
flowchart LR
    A([👤 User]) -->|Search / Filter| B[React Client]
    B -->|Redux State| C[User / Theme Slices]
    B -->|API Request| D[Node.js API]
    D -->|Query| E[(Database\nListings)]
    E -->|Results| F([🏡 Property Listings])
    F -->|View Details| G[Listing Page]

    style A fill:#FFD700,color:#000,stroke:#FFD700
    style D fill:#0a0a0a,color:#FFD700,stroke:#FFD700
    style E fill:#47A248,color:#fff,stroke:#47A248
    style F fill:#000,color:#FFD700,stroke:#FFD700
```

---

## 🛠️ Technology Stack

<div align="center">

| Layer | Technologies |
|:------|:-------------|
| 🎨 **Frontend** | React, Vite, Tailwind CSS |
| ⚙️ **Backend** | Node.js, Express (or preferred framework) |
| 🧠 **State** | Redux (user, theme) |
| 🔧 **Version Control** | Git / GitHub |

</div>

---

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

**Step 1 — Clone the repository**

```bash
git clone https://github.com/NietoDeveloper/RealEstateFinder
cd RealEstateFinder
```

**Step 2 — Install frontend dependencies**

```bash
cd client
npm install
```

**Step 3 — Install backend dependencies**

```bash
cd ../api
npm install
```

### Running the Application

**Start the backend**

```bash
cd api
npm start
```

The backend runs on `http://localhost:3000` by default.

**Start the frontend**

```bash
cd client
npm run dev
```

The frontend runs on `http://localhost:5173` by default (Vite's default port).

---

## 🧑‍💻 Development

- **Frontend:** Uses React with Vite for fast development and Tailwind CSS for styling.
- **Backend:** Node.js with Express (or your preferred framework) for API endpoints.
- **Environment Variables:** Create `.env` files in `/client` and `/api` for configuration (e.g., API URLs, ports).

---

## 📦 Build for Production

**Build the frontend**

```bash
cd client
npm run build
```

Outputs to `/client/dist`.

**Serve the backend**

Ensure the backend is configured to serve the frontend's static files if needed.

---

## 👨‍💻 Author

**Manuel Nieto (NietoDeveloper)**
Software Developer
GitHub: [@NietoDeveloper](https://github.com/NietoDeveloper)

---

## 📄 License

This project is licensed under the **MIT License**.

<div align="center">

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=120&section=footer&animation=fadeIn" width="100%"/>

</div>
