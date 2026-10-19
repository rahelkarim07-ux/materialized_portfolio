# RK://SYS_OPS — Materialized DevSecOps Portfolio

A modern, responsive, terminal-inspired personal portfolio that serves as an interactive DevSecOps operational dashboard and technical showcase. Designed and developed as part of ICT studies (Taitotalo / Metropolia UAS Open Path).

🌐 **Live Demo:** <https://rahelkarim07-ux.github.io/Rahel-Materialized-portfolio/>

## ⚡ Key Features

* **Pure CSS Background Engine:**
  * GPU-accelerated, downward-scrolling 3D perspective grid (`transform: translateY`).
  * Falling electric-cyan data streams (Cyber Rain) without heavy external libraries or JavaScript performance overhead.

* **Materialize CSS Architecture:**
  * Modular grid layout (`col s12 m4`, `container`, `valign-wrapper`).
  * Interactive modal windows (`.modal`) for deep technical and architectural project breakdowns.
  * Centralized tabs (`.tabs`) for technologies, work experience, and certification roadmaps.
  * Fully responsive mobile navigation drawer (`.sidenav`).

* **DevSecOps & Linux Telemetry:**
  * Terminal-emulated system status monitor (`node_inspector.sh`).
  * Direct links to public GitHub repositories and quality assurance models (UML diagrams, test plans).

## 🛠️ Tech Stack

| Domain | Technologies & Tools |
| :--- | :--- |
| **Frontend UI** | HTML5, Materialize CSS v1.0.0, FontAwesome 6, Google Material Icons |
| **Typography** | `JetBrains Mono` (console/code), `Plus Jakarta Sans` (body text) |
| **Graphics & FX** | Pure CSS3 (Keyframes, Perspective, Backdrop-filter, Radial Gradients) |
| **Version Control & CI/CD** | Git, GitHub Desktop, GitHub Pages |
| **Contact Uplink** | Formspree / Mailto compatible form structure |

## 📂 Project Structure

```text
Rahel-Materialized-portfolio/
│
├── Assets/
│   └── Rahel_Karim_CV.pdf    # Downloadable curriculum vitae
├── index.html                # Semantic markup & Materialize components
├── style.css                 # Theme variables, animations & cyber background engine
└── README.md                 # Project technical documentation
```

## 🚀 Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/rahelkarim07-ux/Rahel-Materialized-portfolio.git
   ```

2. **Navigate to the directory:**
   ```bash
   cd Rahel-Materialized-portfolio
   ```

3. **Launch in browser:**
   * Open `index.html` directly in your browser or launch it using VS Code **Live Server**:
     ```bash
     # Or run with Python's built-in HTTP server:
     python -m http.server 8000
     ```
   * Open `http://localhost:8000` in your browser.

## 👨‍💻 Author

**Rahel Karim**
* GitHub: [@rahelkarim07-ux](https://github.com/rahelkarim07-ux)
* LinkedIn: [Rahel Karim](https://linkedin.com/in/rahel-k-11b4a2359)
* Email: [rahel.karim7@yahoo.fi](mailto:rahel.karim7@yahoo.fi)
* Location: Espoo, Finland

## 📄 License

This project is licensed under the [MIT License](LICENSE). Feel free to explore, fork, and learn from the codebase.
