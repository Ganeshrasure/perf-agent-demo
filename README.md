# ⚡ Frontend Performance AI Agent

An automated, LLM-powered monitoring agent that captures frontend performance regressions (Core Web Vitals, INP, LCP) and automatically suggests localized code optimizations.

---

## 🚀 The Problem
Engineering teams usually find out about poor frontend performance or main-thread blockages only **after** frustrated users complain. Modern monitoring systems alert you that a problem exists, but developers still have to manually dive through code, profile timelines, and track down root-cause assets to fix it.

## 🛠️ Our Solution
This project creates an intelligent automated loop:
1. **Detects** a drop in frontend metrics (e.g., LCP spikes, interaction lockouts).
2. **Analyzes** the specific codebase context causing the drop using an LLM.
3. **Optimizes** and suggests code-level rewrites instantly to lower Core Web Vitals back beneath healthy thresholds.

---

## 🧱 Project Architecture & Stack

- **Framework:** Next.js 15 (App Router)
- **Styling:** Tailwind CSS (Responsive Dark Dashboard)
- **AI Engine Simulation:** Deterministic JSON Response Pipeline 

> 💡 **Hackathon Note:** To ensure absolute presentation reliability under volatile venue Wi-Fi and bypass strict live API token rates during rapid judging loops, this project implements a specialized network-simulated Mock API layer (`/api/analyze`). It accurately mimics complex Abstract Syntax Tree (AST) code diagnostics and LLM response outputs without live cloud dependencies.

---

## 📁 Repository Structure

```text
perf-agent-demo/
├── app/
│   ├── api/
│   │   └── analyze/
│   │       └── route.js      # AI Diagnostic Automation API 
│   ├── page.js               # Performance Control Dashboard UI
│   ├── layout.js             # Global Next.js App Context
│   └── globals.css           # Tailwind Utility Declarations
├── public/                   # Asset folder
├── package.json              # Dependencies & Scripts
└── README.md                 # Project Documentation
