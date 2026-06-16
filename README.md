# Canoryn Public Releases

<p align="center">
  <img src="https://canoryn.app/logo.svg" alt="Canoryn Logo" width="128" height="128" />
</p>

<p align="center">
  <strong>Build private, local-first AI agents for your Mac.</strong>
</p>

<p align="center">
  <a href="https://canoryn.app"><img src="https://img.shields.io/badge/Website-canoryn.app-000000?style=flat-square" alt="Website" /></a>
  <a href="https://canoryn.app/docs"><img src="https://img.shields.io/badge/Documentation-docs-blue?style=flat-square" alt="Docs" /></a>
  <a href="https://github.com/procodeai/canoryn-releases/releases/latest"><img src="https://img.shields.io/github/v/release/procodeai/canoryn-releases?style=flat-square&color=orange" alt="Latest Release" /></a>
  <img src="https://img.shields.io/badge/Platform-macOS%2014%2B-lightgrey?style=flat-square" alt="Platform" />
  <img src="https://img.shields.io/badge/Status-Beta-brightgreen?style=flat-square" alt="Status" />
</p>

---

Public releases for **Canoryn** — a native, local-first AI agent workspace for macOS. This repository hosts the public beta builds (`.dmg`) and is the central place to track releases. The app's source is private; only the build artifacts are published here.

Found a bug or have a request? Please open an issue on our public [Issue Tracker](https://github.com/procodeai/canoryn-issues/issues).

---

## Key Features

*   📐 **Visual Architect:** Compose your own agents on a canvas — wire AI models, logic, and native macOS actions into repeatable workflows, saved as portable `.cryn` files.
*   🎙️ **Talk or type:** Drive Canoryn by voice (push-to-talk or continuous) or chat — it acts on your apps and system.
*   🔑 **Bring Your Own Models:** Run fully local models via Ollama, or connect your own cloud keys (OpenAI, Anthropic).
*   🧠 **Personalized Memory:** Local, private context that persists across sessions — nothing leaves your Mac.
*   🔒 **Local-First & Private:** Workflows, settings, and keys stay on your device; secrets live in the macOS Keychain.
*   🪶 **Native & Lightweight:** Built natively in Xcode for macOS — the whole app is ~20 MB.

---

## Installation & Setup

Canoryn is in open public beta. During beta we distribute outside the paid Apple Developer Program, so the build is **not notarized yet** — macOS shows a one-time security prompt on first launch. Notarized builds (no prompt) ship once our Apple Developer ID is set up.

### 1. Download & move

1.  Download the latest build from the [Releases](https://github.com/procodeai/canoryn-releases/releases/latest) page, or use the [direct download link](https://github.com/procodeai/canoryn-releases/releases/latest/download/Canoryn.dmg).
2.  Open the `.dmg` and drag **Canoryn** into your `/Applications` folder.

### 2. Open it past Gatekeeper (one time)

On first launch macOS will say it *"could not verify Canoryn is free of malware."* Use either method:

#### Option A — Terminal (fastest)

```bash
xattr -dr com.apple.quarantine /Applications/Canoryn.app
```

Then open Canoryn normally from Applications or Launchpad.

#### Option B — System Settings

1.  Double-click **Canoryn**; on the warning, click **Done** (not "Move to Trash").
2.  Open **System Settings → Privacy & Security**.
3.  Scroll to the **Security** section — you'll see *"Canoryn was blocked to protect your Mac."* Click **Open Anyway**.
4.  Authenticate with Touch ID or your password, then click **Open Anyway** once more.

You only need to do this once per install.

---

## System Requirements

*   **OS:** macOS 14.0 (Sonoma) or newer.
*   **Hardware:** Universal build (Apple Silicon & Intel). Apple Silicon (M1 or newer) is recommended for running local models via Ollama; Intel Macs are supported but local inference is slower.

---

## Helpful Links

*   **Website:** [canoryn.app](https://canoryn.app)
*   **Documentation:** [canoryn.app/docs](https://canoryn.app/docs)
*   **Report a bug:** [canoryn-issues](https://github.com/procodeai/canoryn-issues/issues)
*   **Studio:** [procodeai.com](https://procodeai.com)
