# 📦 portfolioos-apps

This repository contains `.zip` application packages for **PortfolioOS** — a web-based simulated operating system.

Each `.zip` file is a self-contained app that can be loaded and run in a separate window inside PortfolioOS.

---

## 💡 How It Works

- Apps are loaded via `.zip` files using `<iframe>` and communicate with PortfolioOS through the `postMessage` API.
- Each zip package must include an `index.html` at the root, along with any necessary assets (JavaScript, CSS, images, etc.).

---

## 📁 App Package Structure

Inside each `.zip` file:

