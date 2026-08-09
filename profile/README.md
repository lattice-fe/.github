<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/lattice-fe/.github/main/branding/lattice-wordmark.svg">
    <img alt="Lattice" src="https://raw.githubusercontent.com/lattice-fe/.github/main/branding/lattice-wordmark.svg" width="320">
  </picture>

  <p><b>Fast file exploration, sub-10ms full-text search, and in-app code tooling.</b></p>

  <p>
    <a href="https://github.com/lattice-fe/lattice">Lattice App</a> &middot;
    <a href="https://github.com/lattice-fe/lattice/releases">Releases</a> &middot;
    <a href="https://github.com/lattice-fe/lattice/blob/master/docs/cli.md">CLI Guide</a> &middot;
    <a href="https://github.com/lattice-fe/lattice/blob/master/docs/SKILL.md">Agent Skill</a>
  </p>
</div>

---

### About Lattice

Lattice is a modern desktop file explorer built for speed and developer workflows. It brings instant full-text SQLite search, an in-app multi-language code editor, live Markdown/HTML split previews, Chrome-style tab groups, and a companion terminal CLI to everyday file management.

---

### Repositories

| Repository | Description | Status |
| :--- | :--- | :--- |
| **[lattice](https://github.com/lattice-fe/lattice)** | The core desktop file explorer (Tauri 2, React 19, Rust) with SQLite FTS5 search, in-app code editor, tab groups, and `lat` CLI. | 🚀 Active |
| **[.github](https://github.com/lattice-fe/.github)** | Organization profile and shared assets. | 📦 Active |

---

### Features & Highlights

- **Instant Full-Text Search:** Sub-10ms queries powered by SQLite FTS5 and bm25 ranking across source files and documents.
- **Built-in Code Editor & Previews:** In-app syntax highlighting, find & replace (`Ctrl+F`/`Ctrl+H`), real-time status bar, live Markdown tables, and interactive sandboxed HTML previews.
- **Tab Groups & Drag Reorder:** Chrome-style color-coded tab groups with collapse/expand counts and titlebar drag-and-drop.
- **Spotlight Launcher:** Global `Alt+Space` command palette with math evaluation (`=`), app launching (`>`), and category filtering (`@kind`).
- **`lat` CLI Companion:** Shared zero-overhead terminal binary for instant search queries, previews, and GUI reveal hand-offs.
- **Agent Skill:** Built-in skill definitions and JSON output APIs for AI coding assistants.

---

<div align="center">
  <sub>Built with Rust, Tauri 2, and React 19 &middot; Released under the MIT License</sub>
</div>
