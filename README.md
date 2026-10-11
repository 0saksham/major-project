# Team Wolfs · Major Project Presentation Website

**Project Title:** *A Blockchain-Verified Dynamic Controller for Multi-LLM Orchestration on Distributed Compute Clusters*  
**Team ID:** CSE27-266 | **Team Name:** Team Wolfs  
**Authors:** Saksham Godiyal (2319484) & Anubhav Semwal (2318445)  
**Supervisor / Guide:** Ms. Manika Manwal, Assistant Professor, Department of CSE  
**Institution:** Graphic Era Hill University, Dehradun, Uttarakhand  
**Date:** October 2026  

---

## 🚀 Live Presentation Overview

This is an interactive, scroll-driven, highly animated presentation website built to replace a traditional slide deck for the **Major Project Progress Report 1** defense.

### Key Interactive Features
- **3D Holographic Cluster Canvas**: Interactive 3D visualization of the Coordinator (RPi 5), 3 Worker Nodes (RPi 5), and Jetson Nano GPU with live traveling data pulses and mouse-tilt physics.
- **Physical Build Hardware Showcase**: Real high-resolution laboratory photos of the 4-node Raspberry Pi 5 cluster in its acrylic rack alongside validated empirical metrics (**6.13× speedup**, **1600× less inter-node transfer**).
- **Interactive Routing Weight Simulator**: Live sliders for $\alpha$ (node load), $\beta$ (latency), and $\gamma$ (specialisation tag) that auto-normalize and calculate worker scores in real time.
- **Interactive Blockchain Tamper Demo**: Click any entry to tamper with routing decisions or outputs; watch downstream SHA-256 hashes scramble with red `CHAIN BROKEN` alerts, then click "Restore Chain" for instant green verification.
- **Complete Literature Survey Visualizations**: Dual Recharts distribution graphs (28 papers across 7 themes and 1999–2026 publication timeline) plus interactive orbital paper chips.
- **Slide Presentation Controller**: Floating dock with slide counters, keyboard arrow navigation (`Left`/`Right` arrow keys), and pure Web Audio API synthesized sci-fi sound effects.
- **Appendix & 28 References Modal**: Searchable, theme-filtered bibliography of all 28 citations with one-click citation copying, detailed comparison matrix (zkLLM vs opML vs Our Ledger), security boundaries, and full hardware/software specification tables.

---

## 🛠️ How to Run Locally

### Option 1: Static Web Server (Instant)
Run in powershell or terminal:
```bash
npx --yes serve -p 3000 .
```
Then open your browser at:
- **`http://localhost:3000/`** (or `http://localhost:3000/index.html` / `http://localhost:3000/detail.html`)

### Option 2: Direct File Open
You can also double-click `index.html` or `detail.html` directly to open in Chrome, Edge, or Firefox!

---

## 📁 File Structure

```
web_explain/
├── index.html              # Master interactive presentation website (Self-contained)
├── detail.html             # Synced presentation document
├── assets/
│   ├── cluster_pi_build1.png  # Physical hardware photo: Front stack
│   ├── cluster_pi_build2.png  # Physical hardware photo: Network & power
│   └── cluster_pi_full.png    # High-resolution cluster laboratory build
├── extracted_refs.txt      # Extracted bibliography references from the project report
└── README.md               # Presentation guide & documentation
```

---

## ⌨️ Presentation Keyboard Controls
- **`Right Arrow` / `Page Down`**: Jump to next presentation section
- **`Left Arrow` / `Page Up`**: Jump to previous presentation section
- **`Escape`**: Close the Appendix & References modal
- **`Audio FX Toggle`**: Enable/disable futuristic UI sound synthesis
