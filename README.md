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
### Future Improvement
Instead if doing the POST via REST maybe I could do it with cURL
Offload the upload process to a worker or async, to keep the electron main process "free"
Implement Progress bar
Implement Retry functionality if upload fails at 95%, retry and with exponential backoff
Implement compression so no matter the source the POSTed file will be small thus decreasing time-to-view (the complete time block from the moment it gets uploaded to the API until the time you can share the link with friends)

### Built With

- [Electron](https://www.electronjs.org/) — desktop framework
- Vanilla HTML / CSS / JS — no front-end framework

---
