# RoboEat - Restaurant Website

RoboEat is a responsive, multi-page restaurant website built as a graduation project for **Robogarden** Frontend Development course. The platform showcases modern web layouts, interactive UI elements, and input validation.

## 🚀 Live Demo
You can view the live project hosted on GitHub Pages here: **https://abanoub-ateya.github.io/Restaurant_Website/**

---

## 📋 Project Specifications & Features

This project implements the core objectives and requirements defined by the course evaluation criteria:

### 1. Global Layout (All Pages)
* **Header Navigation:** Built using a responsive Bootstrap Navbar featuring custom CSS styles that apply a distinct background color transition block when hovering over hyperlinks.
* **Footer:** Clean, standard copyright line centered across the bottom of all views.

### 2. Home Page (`index.html`)
* **Dynamic Banner Slider:** Implements a three-image slider using the Bootstrap Carousel component.
* **Responsive Menu Grid:** Displays available menu selections utilizing Bootstrap Cards structured within a flexible grid changing based on the viewport layout:
  * **Laptop/Desktop (`lg`):** 3 menu cards per row.
  * **Tablet (`md`):** 2 menu cards per row.
  * **Mobile device:** 1 menu card per row stacked vertically.
* **Interactive Toggles:** Leverages jQuery click event listeners to let users "Like" or "Dislike" individual food items, dynamically swapping element states, text elements, and background accent colors.

### 3. About Us Page (`about.html`)
* Contains creative overview sections highlighting the backstory, values, and dining environment of the restaurant arranged neatly alongside imagery using standard grid boundaries.

### 4. Contact Us Page (`contact.html`)
* Contains a structured communication form collecting a visitor's `Name`, `Email`, `Phone`, and `Message` utilizing proper Bootstrap structure controls.
* **Client-Side Form Validation:** Processes form execution locally via jQuery to verify all required text segments contain information. Triggers descriptive inline warnings (e.g., *"The Name field is required"*) if empty strings are detected, and showcases a success confirmation banner when validation passes seamlessly.

---

## 🛠️ Built With

* **HTML5** & **CSS3** - Core markup structure and custom semantic properties.
* **Bootstrap v5.1** - Grid layout mechanics, responsive utility tags, slider components, and form control designs.
* **jQuery v3.6.0** - Operational DOM manipulation, toggling logic, and conditional input verification metrics.
* **Font Awesome** - High-quality iconography sets for navigation anchors and button indicators.

---

## 📂 Local Directory Structure

```text
roboeat-project/
│
├── index.html          # Main landing page featuring the carousel and menu cards
├── about.html          # About page presenting background context
├── contact.html        # Contact form with validation scripts
├── style.css           # Custom presentation modifications and link transitions
└── README.md           # Documentation file
