# Smart Pest Elimination System — Technical Overview

An interactive technical overview of the IoT + AI/ML hybrid cockroach detection and elimination system.

## 🚀 Live Demo

Deploy this as a GitHub Pages site — it's a single `index.html` file with no build step required.

## Deployment to GitHub Pages

### Option 1: Direct upload
1. Create a new GitHub repository
2. Upload `index.html` to the root of the repo
3. Go to **Settings → Pages**
4. Under **Source**, select `Deploy from a branch`
5. Select `main` branch and `/ (root)` folder
6. Click **Save**
7. Your site will be live at `https://<username>.github.io/<repo-name>/`

### Option 2: Git CLI
```bash
git init
git add index.html README.md
git commit -m "Initial commit: Smart Pest Elimination System"
git branch -M main
git remote add origin https://github.com/<username>/<repo-name>.git
git push -u origin main
```
Then enable GitHub Pages in repo Settings as above.

## Features

- **5 Interactive Tabs**: Overview, Trap Unit, Detection Flow, Floor Plan, Kill Methods
- **Animated Diagrams**: Auto-cycling operation sequences with SVG animations
- **No Build Step**: Pure HTML + React via CDN — works as a single file
- **Responsive**: Works on desktop and mobile
- **Clean Design**: Professional light theme with warm earth tones

## Technology Stack

- React 18 (via CDN)
- Babel Standalone (in-browser JSX transform)
- Pure SVG diagrams (no image dependencies)
- Google Fonts: DM Sans + JetBrains Mono

## System Overview

The Smart Pest Elimination System is a chemical-free, autonomous IoT solution for cockroach detection and elimination that is safe for humans and pets. It uses:

- **AI Detection**: NVIDIA Jetson Orin Nano + YOLOv8-nano CNN for species classification
- **Multi-Sensor Safety**: PIR + IR camera + acoustic + BLE pet beacons with fail-safe interlocks
- **Cascading Kill**: Electric field grid (1.4kV) → IR heat (70°C) → Cold atmospheric plasma
- **IoT Connected**: MQTT telemetry, real-time dashboard, mobile alerts, OTA updates

## Patent Status

Patent application in preparation. See accompanying patent specification document.

## License

All rights reserved. This technical overview is provided for demonstration purposes.
