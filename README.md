# 🍳 RecipeJS – Functional Cooking Companion

RecipeJS is a modern, interactive recipe web application built using **HTML, CSS, and JavaScript**, with a strong focus on **functional programming principles** and clean code architecture.

The app allows users to browse recipes, filter and sort them, search in real time, expand recipes to view ingredients and steps, and save favorite recipes with persistent storage.

## ✨ Features

### 🧱 Core Functionality
- Dynamic rendering of recipe cards from JavaScript data
- Responsive and clean UI using CSS Flexbox
- Data-driven UI (no hardcoded recipe HTML)

### 🔘 Filters & Sorting
- Filter recipes by difficulty (Easy, Medium, Hard)
- Quick recipes filter (under 30 minutes)
- Favorites-only filter
- Sort recipes by:
  - Name (A–Z)
  - Cooking time (fastest first)

### 📂 Expandable Recipe Details
- Toggle buttons for:
  - Ingredients list
  - Cooking steps
- Support for **nested cooking steps**
- Recursive rendering for unlimited step depth

### 🔍 Search (Debounced)
- Real-time search by:
  - Recipe title
  - Description
  - Ingredients
- Debouncing used to improve performance

### ❤️ Favorites (Persistent)
- Mark recipes as favorites
- Favorites stored using `localStorage`
- Favorites persist after page refresh

### 🔢 Recipe Counter
- Displays number of visible recipes
- Updates dynamically with filters, search, and sorting

---

## 🧠 Key Concepts & Technologies Used

### JavaScript
- ES6+ syntax (`const`, `let`, arrow functions, template literals)
- Functional programming:
  - Pure functions
  - Higher-order functions (`map`, `filter`, `sort`)
- IIFE (Immediately Invoked Function Expression) for encapsulation
- Recursion for nested step rendering
- Event delegation for dynamic elements
- Debouncing for search performance
- `localStorage` for persistent data

### Web Technologies
- Semantic HTML5
- CSS Flexbox
- Responsive design principles

---
edited here !!!!

