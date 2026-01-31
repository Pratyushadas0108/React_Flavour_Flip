# 🍽️ FlavourFlip

**FlavourFlip** is a modern, interactive recipe discovery and cooking companion application built with **React**, featuring a **unique flip-book style recipe viewer** and comprehensive cooking tools.

---

## 📄 Project Resources

- 📘 **Project Report**  
  https://drive.google.com/file/d/1twPcVZjtJHr-nPKZn4sVK4eBezHqtpB7/view?usp=sharing

- 🎥 **Project Demo Video**  
  https://drive.google.com/file/d/1cNSbnDJrn_HtN2jmopbmN4mq5ah5blmV/view

- 🧠 **Project Code Explanation Video**  
  https://drive.google.com/file/d/1g941Nc3S0b9Z1o5F75npprhIrjtf5h8a/view

---

## ✨ Features

### 🔍 Recipe Discovery
- Smart search with advanced filters (cuisine, diet, prep time)
- Trending recipes powered by Spoonacular API
- Create and manage your own local recipes
- Responsive masonry grid layout

### 📖 Interactive Flip-Book Viewer
- Elegant page-flipping recipe experience
- Ingredients, instructions & nutrition info
- Touch & swipe support for mobile devices

### 👨‍🍳 Cooking Mode
- Step-by-step interactive cooking guide
- Progress tracking with celebration animation
- Fullscreen distraction-free interface

### 📚 Personal Cookbook
- Save favorites from Spoonacular or local recipes
- 3D shelf-style cookbook view
- Edit and delete custom recipes

### 🛒 Shopping List
- Quickly add grocery items
- Check off items while shopping
- Persistent local storage

### 🎨 Theme & Design
- Dark / Light mode toggle
- Glassmorphism UI
- Smooth animations with Framer Motion
- 3D hero scene using React Three Fiber

### 👤 User Profiles
- Secure login & signup
- Personal cooking stats
- Auto-generated avatars via DiceBear API

---

## 🚀 Tech Stack

### Frontend
- React 18.2
- React Router DOM
- Vite
- Tailwind CSS

### UI & Animation
- Framer Motion
- Lucide React
- React PageFlip
- React Parallax Tilt
- React Masonry CSS
- React Confetti

### 3D Graphics
- Three.js
- React Three Fiber
- React Three Drei

### API & Data
- Axios
- Spoonacular API
- JSON Server (mock backend)

---

## 📦 Installation

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn

### Setup

```bash
git clone https://github.com/Pratyushadas0108/React_Flavour_Flip.git
cd React_Flavour_Flip
npm install
```

---

### Environment Setup

Create a `.env` file in the project root:

```env
VITE_SPOONACULAR_API_KEY=your_api_key_here
```

---

### Run the Application

```bash
npm run dev:full
```

Or run separately:

```bash
# Terminal 1 - Frontend
npm run dev
```

```bash
# Terminal 2 - JSON Server
npm run server
```

Open in browser:  
http://localhost:5173

---

## 📁 Project Structure

```bash
Flavour-Flip/
├── src/
│   ├── components/
│   │   ├── 3d/
│   │   ├── layout/
│   │   └── ui/
│   ├── context/
│   │   ├── AuthContext.jsx
│   │   └── ThemeContext.jsx
│   ├── pages/
│   │   ├── LandingPage.jsx
│   │   ├── DiscoverPage.jsx
│   │   ├── RecipeDetailPage.jsx
│   │   ├── CookbookPage.jsx
│   │   ├── CookingModePage.jsx
│   │   ├── ProfilePage.jsx
│   │   ├── AuthPage.jsx
│   │   └── ShoppingListPage.jsx
│   ├── services/
│   │   └── api.js
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── db.json
├── index.html
├── package.json
├── tailwind.config.js
└── vite.config.js
```

---

## 🛠️ Available Scripts

```bash
npm run dev
npm run server
npm run dev:full
npm run build
npm run preview
npm run lint
```

---
