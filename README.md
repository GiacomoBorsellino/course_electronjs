## 📘 `README-Electron.md`

```markdown
# Introduzione a Electron.js

**Electron.js** è un framework open-source mantenuto da GitHub/OpenJS Foundation per creare **app desktop multipiattaforma** usando HTML, CSS e JavaScript :contentReference[oaicite:3]{index=3}.  
Integra Chromium e Node.js in un unico runtime, permettendo di usare tecnologie Web lato desktop :contentReference[oaicite:4]{index=4}.

**Ideale per**:
- App desktop per Windows, macOS, Linux
- Riutilizzo di competenze Web esistenti
- Accesso a API native (file system, notifiche…)

**Punti chiave**:
- Architettura a processi: “main” (logica) + “renderer” (UI)
- Packaging e distribuzione tramite Electron Forge/Builder
- Ecosistema ricco e popolare (VS Code, Slack, Discord…)

**Prerequisiti**:
- Node.js/npm
- Conoscenza di JavaScript/HTML/CSS

**Primi passi**:
```bash
npx create-electron-app nome-app
cd nome-app
npm start
