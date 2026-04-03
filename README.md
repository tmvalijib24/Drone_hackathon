# Brahmos Defense 🎯
**Automated Intercept & Guidance Intelligent System (Deterministic Evolution Engine)**

[![Hackathon: AI Without the API](https://img.shields.io/badge/Hackathon-AI_Without_API-00f2ff?style=flat-square)](#)
[![Tech Stack: Three.js & Chart.js](https://img.shields.io/badge/Tech-Three.js_|_Chart.js-yellow?style=flat-square)](#)
[![Logic: Deterministic](https://img.shields.io/badge/Logic-Deterministic_Control_Theory-green?style=flat-square)](#)

Brahmos Defense is an interactive, browser-based aerospace defense simulation built to demonstrate **"AI without the API."** It proves that complex, adaptive intelligence can be achieved purely through deterministic control theory—without relying on black-box Large Language Models (LLMs) or hidden inference.

## 🧠 The Philosophy: Intelligence by Design
Modern software often borrows intelligence from external generative models. Brahmos Defense flips this paradigm. The intelligence resides 100% in the code. The system learns to intercept highly evasive targets by utilizing a **Deterministic Proportional Feedback Loop**, optimizing its flight paths in real-time while remaining strictly bound by the laws of physics and hardware limitations.

## ✨ Key Features
* **Zero API Dependencies:** All learning logic is executed locally and deterministically.
* **100% Explainability:** A live "Neural Logic Ledger" provides a fully transparent audit trail of every mathematical micro-step the system takes to correct its errors.
* **Proportional Navigation (PN):** Implements real-world aerospace guidance math, transitioning from pure pursuit to lead pursuit as the system learns.
* **Hardware vs. Software Diagnostics:** The system understands physical reality. When mathematical optimization hits an aerodynamic ceiling ($N=4.2$), it accurately diagnoses a hardware bottleneck (tube saturation) rather than hallucinating impossible solutions.
* **Dynamic Visualization:** Fully rendered in 3D using `Three.js` with real-time learning curves charted via `Chart.js`.

## ⚙️ How It Works (The Logic)
The "brain" of Brahmos Defense operates on a classical machine learning gradient-descent concept, adapted for physics:
1. **The Objective (Loss Function):** After every wave, the system calculates its exact failure rate (e.g., if 60% of targets leak, Error = 0.40).
2. **The Weight (Navigation Gain):** The system controls a single variable—Navigation Gain ($N$)—which dictates how aggressively an interceptor turns to establish a collision course.
3. **The Optimization:** It multiplies the error by a strict learning rate, taking mathematically proportional "micro-steps" to update $N$. High errors trigger large corrections; small errors trigger microscopic fine-tuning (creating the classic S-Curve).
4. **The Physical Constraint:** The math is capped at an aerodynamic G-limit. Once reached, the system transitions to evaluating its physical constraints (reload speed, interceptor capacity).

## 🚀 Installation & Usage
Brahmos Defense requires zero build steps, zero package managers, and zero API keys. 

1. Clone or download this repository.
2. Open `index.html` in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Select your threat profile (Linear, Sinusoidal, Evasive) and click **Start Training**.
4. Watch the Neural Ledger and the Chart as the system teaches itself to defend the origin point.

## 🛠️ Tech Stack
* **Core Logic:** Vanilla JavaScript (ES6+)
* **3D Rendering:** Three.js (WebGL)
* **Analytics Visualization:** Chart.js
* **UI/Styling:** Tailwind CSS (via CDN)
