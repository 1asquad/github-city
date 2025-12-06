# 🏙️ GitHub City 3D Viewer


[![Live Demo](https://img.shields.io/badge/🚀_Launch-Live_City_Viewer-00ffcc?style=for-the-badge&logo=github)](https://1asquad.github.io/github-city/)
[![Three.js](https://img.shields.io/badge/Three.js-3D_Engine-white?style=flat-square&logo=three.js&color=black)](https://threejs.org/)
[![GitHub API](https://img.shields.io/badge/GitHub-API_Integration-181717?style=flat-square&logo=github)](https://docs.github.com/en/rest)

**Turn your GitHub contributions into a Cyberpunk Metropolis.**

This project is a 3D visualization tool that procedurally generates a city based on any user's GitHub profile. Each building represents a repository, with its height and appearance determined by real code metrics.

## 🌟 Key Features

* **Procedural Generation:** Buildings are generated in real-time based on repository size.
* **Language-Based Coloring:** Python projects are blue, JavaScript is yellow, Solidity is dark grey, etc.
* **Dynamic Textures:** Windows are drawn procedurally on a canvas texture to create a lit skyscraper effect.
* **Interactive UI:** Search for any GitHub user to generate their unique city.
* **Zero-Server Architecture:** Runs entirely in the browser using the GitHub Public API.

## 🕹️ How to Use

1.  Click the **[Live Demo](https://1asquad.github.io/github-city/)** button.
2.  Enter a GitHub username (e.g., `1asquad`, `torvalds`, `facebook`).
3.  Press **ENTER** or click **INITIALIZE CITY**.
4.  Explore the city:
    * **Left Click + Drag:** Rotate the camera.
    * **Right Click + Drag:** Pan the camera.
    * **Scroll:** Zoom in/out.

## 🛠️ Tech Stack

* **Core:** HTML5, CSS3, Vanilla JavaScript (ES6+).
* **3D Engine:** [Three.js](https://threejs.org/) (WebGL).
* **Data Source:** GitHub REST API.
