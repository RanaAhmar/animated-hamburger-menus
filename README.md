# Animated Hamburger Menus 🍔

![CSS Version](https://img.shields.io/badge/CSS3-Compatible-blue?style=flat-square&logo=css3)
![License](https://img.shields.io/github/license/RanaAhmar/animated-hamburger-menus?style=flat-square)
![Dependencies](https://img.shields.io/badge/Dependencies-0-success?style=flat-square)

**A premium collection of pure CSS, hardware-accelerated animated hamburger menus.**

Say goodbye to bloated JavaScript animations for your mobile navigation toggles. This repository provides highly optimized, ultra-smooth CSS transitions that transform standard hamburger icons into 'X' close buttons and back.

## 🌟 Key Features

- **Pure CSS Transitions**: No JavaScript required for the animation itself.
- **Hardware Accelerated**: Uses `transform` and `opacity` to ensure buttery smooth 60fps animations on mobile devices.
- **Micro-interactions**: Beautifully crafted easing curves for premium feel.
- **Scalable Vectors**: Uses standard HTML elements (`<div>` and `<span>`), meaning they scale perfectly without pixelation.

## 📚 Table of Contents

- [Installation](#-installation)
- [How to Use](#-how-to-use)
- [Available Animations](#-available-animations)
- [License](#-license)

## 📦 Installation

To include these in your project, simply copy the `hamburgers.css` file into your project.

```html
<link rel="stylesheet" href="path/to/hamburgers.css">
```

## 🚀 How to Use

HTML Structure:
```html
<button class="hamburger hamburger--spin" type="button">
  <span class="hamburger-box">
    <span class="hamburger-inner"></span>
  </span>
</button>
```

JavaScript trigger (To toggle the active state):
```javascript
const hamburger = document.querySelector('.hamburger');
hamburger.addEventListener('click', function() {
  this.classList.toggle('is-active');
});
```

## 🛠 Available Animations

Add any of these modifier classes to your `.hamburger` button to change the animation style:

| Class | Description |
| :




---

## 🚀 Discover More from Stackaura

If you found this tool useful, check out our other high-performance web utilities and follow **Ahmar Hussain** for more open-source excellence.

### 🌟 Featured Projects
- **[Free LLM APIs](https://github.com/RanaAhmar/free-llm-apis)** - A curated list of zero-cost AI endpoints.
- **[Awesome MCP Servers](https://github.com/RanaAhmar/awesome-mcp-servers)** - The ultimate collection of Model Context Protocol implementations.
- **[System Design Cheatsheet](https://github.com/RanaAhmar/system-design-cheatsheet)** - Master complex architectures in minutes.
- **[Next.js SaaS Starter](https://github.com/RanaAhmar/nextjs-saas-starter)** - The fastest way to launch your next product.

### 🔗 Stay Connected
- **Website:** [stackaura.com](https://www.stackaura.com/)
- **Author:** [Ahmar Hussain](https://github.com/RanaAhmar)

---





