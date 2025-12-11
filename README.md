# <div align="center">
  <br />
  <a href="https://www.youtube.com/watch?v=iYOz165wGkQ" target="_blank">
    <img src="public/readme/hero.webp" alt="AI Resume Analyzer" />
  </a>
  <br />

  <div>
    <img alt="React" src="https://img.shields.io/badge/React-4c84f3?style=for-the-badge&logo=react&logoColor=white" />
    <img alt="Tailwind" src="https://img.shields.io/badge/-Tailwind-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" />
    <img alt="TypeScript" src="https://img.shields.io/badge/-TypeScript-black?style=for-the-badge&logo=typescript&color=3178C6" />
    <img alt="Puter.js" src="https://img.shields.io/badge/Puter.js-181758?style=for-the-badge&logoColor=white" />
  </div>

  <h3 align="center">AI Resume Analyzer</h3>
  <p align="center">A fast, client-side app that uses AI to evaluate resumes, score them against job descriptions, and provide actionable feedback.</p>
</div>

## Table of Contents

1. Introduction
2. Tech Stack
3. Features
4. Quick Start
5. Configuration
6. Assets & Resources
7. Contributing
8. License

---

## ✨ Introduction

AI Resume Analyzer helps candidates and recruiters quickly assess resumes using modern browser-based AI tools. Upload resumes, provide a job description, and get an ATS-style score plus strengths, weaknesses, and suggested improvements — all without a custom backend.

This repo contains an interactive front-end built with React + Puter.js for zero-setup auth, storage, and AI integration. It was created to serve as a learning project and a practical tool for resume optimization.

---

## ⚙️ Tech Stack

- React — Component-driven UI
- React Router — Client-side routing
- Puter.js — Browser-native auth, storage, and AI (GPT/Claude/DALL·E/OCR)
- Tailwind CSS — Utility-first styling
- TypeScript — Static types for reliability
- Vite — Fast dev server and builds
- Zustand — Simple state management
- Optional: shadcn/ui for accessible components

---

## 🔋 Key Features

- Browser-only authentication (Puter.js) — no server required
- Upload and manage multiple resumes (PDF, DOCX)
- Parse resume text using OCR when needed
- Compare resumes to a job description and produce:
  - ATS-like match score
  - Bullet-point feedback and suggested edits
  - Highlighted skill and experience gaps
- Responsive, reusable UI components for fast iteration
- Local storage and optional cloud storage via Puter.js

---

## 🤸 Quick Start

Prerequisites
- Git
- Node.js (LTS recommended)
- npm or yarn

Clone the repo:
```bash
git clone https://github.com/SriHarshaBoyina/ai-resume-analyzer.git
cd ai-resume-analyzer
```

Install dependencies:
```bash
npm install
# or
# yarn
```

Start the dev server:
```bash
npm run dev
```

Open http://localhost:5173 in your browser.

---

## 🔧 Configuration

- .env (if applicable)
  - Add any Puter.js keys or other environment variables as instructed in the project docs.
- Puter.js handles auth/storage in-browser; follow the Puter.js quickstart to connect third-party AI providers if you want custom provider keys for GPT/Claude.

---

## 🔗 Assets & Resources

- Video tutorial and walkthrough (if available): https://www.youtube.com/watch?v=iYOz165wGkQ
- Project assets and video kit: https://jsm.dev/resumind-kit
- Puter docs: https://jsm.dev/resumind-puter
- Puter.js SDK: https://jsm.dev/resumind-puterjs

---

## 🙌 Contributing

Contributions are welcome! Suggested workflow:
1. Fork the repo
2. Create a feature branch: git checkout -b feat/your-feature
3. Commit changes and open a pull request with a clear description

Please open issues for bugs or feature requests.

---

## 📜 License

This project is provided under the MIT License. See LICENSE for details.

---

If you'd like, I can:
- commit this README.md into your repository on a new branch and open a PR, or
- tailor the copy to emphasize a tutorial video, specific usage examples, or add screenshots and gifs.
