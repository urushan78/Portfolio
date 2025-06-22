# My Portfolio Website

This is a modern, responsive portfolio website built using **HTML** and **Tailwind CSS**, designed to showcase projects, provide contact information, and demonstrate front-end skills including dark mode, animation, and responsive layouts.

---

## What I Learned

This project helped me understand and apply the following key web development concepts:

- ✅ **Tailwind CSS (Utility-First Framework)**  
  Used for styling everything without writing traditional CSS — with utilities like `bg-gray-900`, `grid-cols-3`, `hover:bg-blue-700`, etc.

- ✅ **Dark Mode with Tailwind (`class` strategy)**  
  Toggled using JavaScript and Tailwind’s built-in dark mode support with class-based switching.

- ✅ **Responsive Design**  
  Handled with Tailwind’s responsive prefixes like `sm:`, `md:`, and `lg:` for layout adjustments on different screen sizes.

- ✅ **Animations**  
  Defined custom `fadeIn` animation using `@keyframes` in `tailwind.config.js` and applied with Tailwind’s `animate-fadeIn` utility.

- ✅ **Grid and Flexbox Layouts**  
  Used both `flex` and `grid` utilities to build responsive sections like the projects gallery.

- ✅ **Semantic HTML**  
  Structured the site using meaningful HTML5 tags like `<header>`, `<section>`, `<footer>`, etc.

---

## Navbar Functionality

The **navigation bar** is built using Tailwind CSS and includes:

- A **logo/title**
- Links to scroll to each section: `Home`, `About`, `Projects`, and `Contact`
- A **dark mode toggle button** (`🌙`) that switches themes when clicked

### How it works:

- The navbar is **fixed at the top** so it stays visible when scrolling.
- On small screens, the nav links are hidden (`md:flex` is used to show them only on medium and larger screens).
- The **dark mode toggle** uses JavaScript to toggle the `dark` class on the `<html>` element. This switches between light and dark styles instantly.
- Tailwind’s transitions and hover states (`hover:text-blue-500`, `transition`) enhance interactivity.

---

## Project Structure

<pre>
project-root/
├── index.html              # Main HTML file with all sections
├── output.css              # Compiled Tailwind CSS styles
├── src/
│   └── input.css           # Source file with Tailwind directives
├── node_modules/           # Installed dependencies
├── tailwind.config.js      # Tailwind config (theme, dark mode, animations)
├── postcss.config.js       # PostCSS setup for Tailwind + autoprefixer
├── package.json            # Project metadata and dependencies
├── package-lock.json       # Exact package versions
├── .gitignore              # Files/folders to ignore in Git
</pre>

---

## ✨ Features

- 🔄 Dark/Light mode toggle
- 📱 Fully responsive (mobile to desktop)
- 🎨 Custom animations
- 🧩 Grid-based project gallery
- 📬 Contact form layout (non-functional demo)
- 🧠 Clean and semantic HTML structure

---

## 🛠 Technologies Used

- HTML5
- Tailwind CSS v3
- PostCSS
- Autoprefixer
- JavaScript (for dark mode toggle)

---

## 📺 View Live

👉 [Live Site](https://portfolio-iota-rust-dlupqfbc1u.vercel.app/)

---
