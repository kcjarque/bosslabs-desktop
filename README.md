# BOSSLABS for Mac and Windows

AI chat and a coding agent that builds apps in a folder on your computer, powered by BOSSLABS AI.

## Download

**Mac**
- **Apple Silicon (M1/M2/M3/M4):** [BOSSLABS-mac-apple-silicon.dmg](https://github.com/kcjarque/bosslabs-desktop/releases/latest/download/BOSSLABS-mac-apple-silicon.dmg)
- **Intel Mac:** [BOSSLABS-mac-intel.dmg](https://github.com/kcjarque/bosslabs-desktop/releases/latest/download/BOSSLABS-mac-intel.dmg)

Not sure which? Apple menu  → **About This Mac**. If it says **Chip: Apple M…**, get Apple Silicon. If it says **Processor: Intel**, get Intel.

**Windows 10/11**
- **Most PCs (Intel/AMD):** [BOSSLABS-windows-setup.exe](https://github.com/kcjarque/bosslabs-desktop/releases/latest/download/BOSSLABS-windows-setup.exe)
- **ARM PCs (Snapdragon / Copilot+ PCs):** the `BOSSLABS-Setup-…-arm64.exe` file on the [latest release](https://github.com/kcjarque/bosslabs-desktop/releases/latest)

## Install on Mac

1. Open the downloaded DMG and drag **BOSSLABS** into **Applications**.
2. Open BOSSLABS from Applications.
3. **First launch only:** this early version isn't signed by Apple yet, so macOS blocks it. Open **System Settings → Privacy & Security**, scroll down, and click **Open Anyway** next to "BOSSLABS was blocked", then confirm. (On older macOS you can instead right-click BOSSLABS → **Open** → **Open**.)
4. Sign in with an API key from your BOSSLABS AI account.

## Install on Windows

1. Run **BOSSLABS-windows-setup.exe**. It installs for your user only (no admin needed) and opens BOSSLABS.
2. **First run only:** this early version isn't code-signed yet, so Windows may show "Windows protected your PC". Click **More info → Run anyway**.
3. Sign in with an API key from your BOSSLABS AI account.
4. Recommended: install [Git for Windows](https://git-scm.com/download/win). The coding agent uses its Git Bash for commands (it falls back to PowerShell without it). For app previews, install [Node.js](https://nodejs.org).

Updates: the app checks for new versions and shows an **Update** button when one is out.

---
© 2025–2026 Bosslabs Technology Inc. Pasig, NCR, Philippines. This repository only hosts release files.
