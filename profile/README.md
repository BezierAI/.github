<div align="center">

<img src="https://raw.githubusercontent.com/BezierAI/.github/main/assets/logo.svg" alt="Bézier Logo" width="120" />

# Bézier

### The Designer Control Loop

*Give designers the same trust in AI that developers have with code.*

[![Status](https://img.shields.io/badge/status-MVP%20Complete-brightgreen)](https://github.com/BezierAI/monorepo)
[![Milestone](https://img.shields.io/badge/milestone-M6%20Distribution-blue)](https://github.com/BezierAI/monorepo)
[![Platform](https://img.shields.io/badge/platform-macOS-lightgrey)](https://github.com/BezierAI/monorepo)

[![Electron](https://img.shields.io/badge/Electron-47848F?logo=electron&logoColor=white)](https://www.electronjs.org/)
[![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Claude](https://img.shields.io/badge/Claude-191919?logo=anthropic&logoColor=white)](https://www.anthropic.com/)

</div>

---

## 🎨 What is Bézier?

Bézier is a desktop application that transforms text prompts into professional designs using AI. Unlike simple image generators, Bézier understands your design as **structured regions** — title, hero, background, footer — giving you precise control over what changes and what stays locked.

**Lock what you love, regenerate the rest.**

```
┌─────────────────────────────────────────────────────────────────┐
│                                                                 │
│     Prompt  ──▶  Generate  ──▶  Review  ──▶  Lock  ──▶  Iterate │
│        │            │             │           │            │    │
│        │            ▼             │           ▼            │    │
│        │      ┌─────────┐        │     ┌─────────┐        │    │
│        │      │ DIR-lite│◀───────┘     │ Regions │        │    │
│        │      │  (JSON) │              │ Locked  │        │    │
│        │      └─────────┘              └─────────┘        │    │
│        │                                                   │    │
│        └───────────────────────────────────────────────────┘    │
│                         Version Timeline                        │
└─────────────────────────────────────────────────────────────────┘
```

---

## ✨ Key Features

| Feature                       | Description                                                              |
| ----------------------------- | ------------------------------------------------------------------------ |
| **🔒 Lock Regions**           | Protect parts of your design while regenerating others                   |
| **🎯 Selective Regeneration** | Change only what you want without affecting locked areas                 |
| **📜 Version Timeline**       | Navigate through design iterations with visual history                   |
| **🔍 Semantic Diff**          | Understand what changed between versions in plain English                |
| **💬 Comments & Review**      | Comment on versions, request changes, approve designs                    |
| **🎨 Quality Validation**     | AI validates generated images match the design specification             |
| **⚡ Local-First**            | Runs on your machine with SQLite — your designs stay private             |

---

## 🛠️ Tech Stack

| Layer                | Technology                     |
| -------------------- | ------------------------------ |
| **Desktop**          | Electron 28                    |
| **Frontend**         | React 18 + TypeScript          |
| **State**            | Zustand                        |
| **Canvas**           | Konva.js / React-Konva         |
| **UI**               | Radix UI + TailwindCSS         |
| **Database**         | SQLite (better-sqlite3)        |
| **AI - Structure**   | Claude API (Anthropic)         |
| **AI - Images**      | Ideogram API                   |
| **Image Processing** | sharp                          |

---

## 📦 Repository

| Package | Description |
|---------|-------------|
| [`monorepo`](https://github.com/BezierAI/monorepo) | Main application monorepo |

---

## 🗺️ Roadmap

### MVP Complete ✅

- [x] **M0**: Foundation (Claude + Ideogram + Database + Storage)
- [x] **M1**: Core Generation Loop (UI + Generation Flow)
- [x] **M2**: Selective Regeneration & Locking
- [x] **M3**: Version Timeline & Semantic Diff
- [x] **M4**: Review & Collaboration
- [x] **M5**: Generation Quality & Validation

### In Progress 🔄

- [ ] **M6**: Distribution & Packaging (code signing, notarization, auto-updates)

### Future 🔮

- [ ] **M7**: Advanced Features (polygon masks, undo/redo, templates)
- [ ] **M8**: Collaboration & Sharing (cloud sync, team features)

---

<div align="center">

**Built with ☕ and AI**

<img src="https://raw.githubusercontent.com/BezierAI/.github/main/assets/logo.svg" alt="Bézier" width="40" />

*Lock what you love, regenerate the rest.*

</div>
