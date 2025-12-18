<img src="https://raw.githubusercontent.com/BezierAI/.github/main/assets/banner.svg" alt="Bézier" width="100%" />

<div align="center">

# Bézier

### AI-Powered Design Generation & Iteration

*From prompt to polished design — lock what you love, regenerate the rest.*

[![Electron](https://img.shields.io/badge/Electron-47848F?logo=electron&logoColor=white)](https://www.electronjs.org/)
[![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)](https://react.dev/)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)](https://www.typescriptlang.org/)
[![Claude](https://img.shields.io/badge/Claude-191919?logo=anthropic&logoColor=white)](https://www.anthropic.com/)

</div>

---

## 🎨 What is Bézier?

Bézier is a desktop application that transforms text prompts into professional designs using AI. Unlike simple image generators, Bézier understands your design as **structured regions** — title, hero, background, footer — giving you precise control over what changes and what stays locked.

```
┌─────────────────────────────────────────┐
│  "Event poster for jazz concert"        │
│            ↓                            │
│  ┌─────────────────────────────────┐   │
│  │ 🔒 Background (locked)          │   │
│  │ 🔓 Title     → "Make it bolder" │   │
│  │ 🔒 Hero      (locked)           │   │
│  │ 🔓 Footer    → "Simplify"       │   │
│  └─────────────────────────────────┘   │
│            ↓                            │
│     Only Title & Footer regenerate      │
└─────────────────────────────────────────┘
```

## ✨ Key Features

| Feature | Description |
|---------|-------------|
| **🎯 Semantic Regions** | AI extracts meaningful regions (title, hero, footer) from your design |
| **🔒 Selective Locking** | Lock regions you love, regenerate only what needs work |
| **📜 Version Timeline** | Navigate through design iterations with visual history |
| **🔍 Semantic Diff** | Understand what changed between versions in plain English |
| **⚡ Local-First** | Runs on your machine with SQLite — your designs stay private |

## 🛠️ Tech Stack

- **Desktop**: Electron + React + TypeScript
- **AI Generation**: Claude (layout) + Ideogram (images)
- **Storage**: SQLite + local filesystem
- **State**: Zustand
- **Canvas**: React Konva

## 📦 Repository

| Package | Description |
|---------|-------------|
| [`monorepo`](https://github.com/BezierAI/monorepo) | Main application monorepo |

## 🗺️ Roadmap

- [x] **M0**: Foundation (Claude + Ideogram + Database + Storage)
- [x] **M1**: Core Generation Loop (UI + Generation Flow)
- [x] **M2**: Selective Regeneration & Locking
- [ ] **M3**: Version Timeline & Semantic Diff
- [ ] **M4**: Review & Collaboration

---

<div align="center">

**Built with ☕ and AI**

*Bézier — where prompts become designs*

</div>

