# Changelog Component

A clean, structured changelog interface built with vanilla HTML and CSS. This project is a completed solution for the Changelog Component challenge provided by [roadmap.sh](https://roadmap.sh/).

## 🎯 Project Overview

This repository contains the source code for a vertical timeline component designed to display product updates, feature releases, and project milestones. The primary focus of this exercise is implementing semantic HTML and utilizing modern CSS layout modules to create a perfectly aligned, visually appealing timeline interface. 

Challenge Link: [https://roadmap.sh/projects/changelog-component](https://roadmap.sh/projects/changelog-component)

## 🛠️ Technologies Used

* **HTML5:** For semantic markup and structured content delivery.
* **CSS3:** For component styling, utilizing both Flexbox (for macro-layout alignment) and CSS Grid (for precision micro-layout of the timeline entries).

## ✨ Technical Highlights

* **Grid-Based Timeline Alignment:** Implements a precise `display: grid; grid-template-columns: 1fr 10px 1fr;` layout on list items to ensure flawless horizontal alignment between timestamps, custom timeline nodes, and descriptive text.
* **Custom Interface Elements:** Features custom-built timeline indicators (dots) and vertical connecting lines utilizing absolute positioning (`position: absolute;`).
* **Interactive Call-to-Action (CTA):** Includes smooth, performant hover transitions on the primary button, utilizing `transform: translateY` and color state changes for better user feedback.
* **Zero Dependencies:** Built entirely with native web technologies, requiring no external frameworks, libraries, or build tools.

## 🚀 Getting Started

As this is a static web project, installation is straightforward and requires no package managers.

1.  Clone this repository to your local machine:
    ```bash
    git clone https://github.com/ramadhanzakki/roadmap-sh-project/tree/main/changelog-component.git
    ```
2.  Navigate to the project directory.
3.  Ensure `index.html` and `style.css` are located in the same root folder.
4.  Open the `index.html` file directly in your preferred web browser. 
5.  *Optional:* For live-reloading during development, serve the directory using an extension like **Live Server** in Visual Studio Code.

---
*Developed as part of the frontend architectural roadmap.*