Disclaimer: This is an **Electron desktop app** (GUI wrapper for the existing Node CLI tool) that watches a folder and uploads clips to Litterbox (temporary file sharing). Currently in a static/styling phase.

---

## Litterbox Clip Watcher

A GUI desktop application that watches a folder and uploads new clips to [Litterbox](https://litterbox.catbox.moe/) — a temporary file hosting service. Built with **Electron**.

> This is the graphical interface version of the original CLI tool.

### Current Status

Still in early development. The UI is currently **static** — focus is on styling and layout.

### TODO

- [ ] **Log window** — display real-time command/output logs
- [ ] **Folder watcher path browser** — select the watched directory via a native file dialog
- [ ] **Scrollable history panel** — persistent, scrollable list of uploaded clips

### Prerequisites

- **Node.js** v22+ (recommended)
- **Yarn** — install globally with: `npm install -g yarn`

### Getting Started

```bash
# Install dependencies
yarn install

# Launch the app
yarn run start
```

### Built With

- [Electron](https://www.electronjs.org/) — desktop framework
- Vanilla HTML / CSS / JS — no front-end framework

---
