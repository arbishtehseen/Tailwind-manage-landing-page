# Manage Landing Page - Tailwind CSS

A responsive, modern landing page for the "Manage" platform built with **Tailwind CSS** and **JavaScript**. This project is based on the popular Frontend Mentor challenge designed to practice layout structure, responsive web design, and utility-first CSS principles.

---

## 🚀 Demo & Repository

* **Repository:** [https://github.com/arbishtehseen/Tailwind-manage-landing-page](https://github.com/arbishtehseen/Tailwind-manage-landing-page)

---

## ✨ Features

* **Fully Responsive:** Customized layouts tailored for mobile, tablet, and desktop viewports.
* **Modern UI:** Clean typography, vibrant call-to-action buttons, and smooth layout grids.
* **Mobile Menu Interactivity:** JavaScript-powered hamburger menu toggle for mobile navigation.
* **Testimonials Slider / Layout:** Showcases user feedback and social proof.
* **Newsletter Form:** Interactive email input field with hover and focus states.

---

## 🛠 Tech Stack

* **HTML5:** Semantic HTML markup.
* **Tailwind CSS:** Utility-first CSS framework for styling and responsive layouts.
* **JavaScript:** Handles DOM interaction (mobile navigation menu).
* **Node.js / npm:** For managing dependencies and building Tailwind assets.

---

## 📂 Project Structure

```text
Tailwind-manage-landing-page/
├── dist/                # Output folder for production CSS
│   └── output.css
├── src/                 # Source files
│   └── input.css
├── images/              # Assets, icons, and background patterns
├── index.html           # Main landing page HTML
├── script.js            # JavaScript for interactive components
├── tailwind.config.js   # Tailwind CSS configuration file
├── package.json         # Project dependencies and scripts
└── README.md            # Project documentation
---
⚙️ Getting Started
Follow these steps to run the project locally on your machine:

1. Clone the Repository
Bash
git clone [https://github.com/arbishtehseen/Tailwind-manage-landing-page.git](https://github.com/arbishtehseen/Tailwind-manage-landing-page.git)
cd Tailwind-manage-landing-page
2. Install Dependencies
Make sure you have Node.js installed, then run:

Bash
npm install
3. Build Tailwind CSS
To compile the Tailwind CSS input file into the output CSS file:

Watch for changes (Development):

Bash
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
Production Build:

Bash
npx tailwindcss -i ./src/input.css -o ./dist/output.css --minify
4. Run the Project
Open index.html directly in your browser or use an extension like Live Server in VS Code.

👤 Author
Arbish Tehseen

GitHub: @arbishtehseen
