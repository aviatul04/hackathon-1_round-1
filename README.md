# hackathon-1_round-1
# 💠 Flexify.css – A Lightweight UI CSS Framework

**Built with ❤️ by Team WE CODE**  
A modular, responsive, and beginner-friendly CSS utility framework designed to simplify front-end development with a clean architecture, reusable components, and easy dark mode support.

---

## 📂 Project Structure
flexify/ ├── index.html # Demo page showcasing the framework ├── docs.html # Developer documentation & usage examples ├── css/ │ ├── base.css # Design tokens, resets, and typography │ ├── grid.css # 12-column responsive grid system │ ├── utilities.css # Utility classes (spacing, text, flex, layout) │ ├── components.css # Prebuilt UI components (btn, card, alert, etc.) └── README.md # Project overview (this file)

---

## 📘 About Flexify.css

Flexify.css is a CSS-only framework that blends the **utility-first power of Tailwind** with the **component simplicity of Bootstrap**. It is built entirely from scratch and does not rely on any existing framework, making it lightweight, customizable, and easy to learn.

---

## ⚙️ How to Use
index.html
A complete demo page showcasing Flexify.css in action. Includes examples of grid usage, buttons, cards, alerts, badges, and dark mode toggle.

docs.html
Developer documentation with code examples, integration instructions, utility class reference, and component previews.

base.css
Includes:

CSS Reset

Global box-sizing

Custom CSS Variables (--spacing-md, --color-primary, etc.)

Base typography and body styles

Light/Dark theme support via .dark class

grid.css
Implements a 12-column responsive grid system using Flexbox:

.row for flex containers

.col-1 to .col-12 for column width

Mobile-first media query behavior

utilities.css
A collection of utility classes:

Spacing: .p-md, .m-sm, .mb-lg

Typography: .text-sm, .text-center, .text-muted

Flexbox: .flex, .justify-between, .align-center

components.css
Contains reusable UI components:

.btn, .btn-primary, .btn-outline

.card, .card-title, .card-body

.alert, .alert-success, .alert-error

.navbar, .badge, .footer

### 🔗 Include in HTML

Paste the following lines inside the `<head>` of your HTML file:

```html
<!-- Flexify Core CSS Files -->
<link rel="stylesheet" href="css/base.css">
<link rel="stylesheet" href="css/grid.css">
<link rel="stylesheet" href="css/utilities.css">
<link rel="stylesheet" href="css/components.css">

🌙 Dark Mode Support
To toggle dark mode, simply add the .dark class to <body>:

html
Copy
Edit
<body class="dark">
  <!-- Content -->
</body>
You can also toggle it dynamically using JavaScript:

javascript
Copy
Edit
function toggleDarkMode() {
  document.body.classList.toggle('dark');
}
🚀 Features
✅ Responsive 12-column Grid

✅ Utility-first Class System

✅ Modular CSS File Structure

✅ Reusable UI Components

✅ CSS Variables & Theming

✅ Dark Mode Support

✅ No JavaScript dependencies

✅ Lightweight & Beginner-Friendly

🛠 Built With
HTML5 & CSS3 (No JS frameworks)

