# Canoryn

<p align="center">
  <img src="https://canoryn.app/logo.svg" alt="Canoryn logo" width="112" height="112" />
</p>

<p align="center">
  <a href="https://github.com/procodeai/canoryn-releases/releases/latest"><img src="https://img.shields.io/github/v/release/procodeai/canoryn-releases?style=flat-square&color=orange" alt="Latest release" /></a>
  <img src="https://img.shields.io/badge/macOS-15.4%2B-lightgrey?style=flat-square" alt="macOS 15.4 or later" />
  <img src="https://img.shields.io/badge/status-beta-brightgreen?style=flat-square" alt="Beta" />
</p>

Canoryn is an agent workspace for your Mac, built natively in Swift. Open a project and chat with an agent that reads, edits, runs and tests it, with every step in view and a question before anything risky. Review and commit what changed, write Markdown documents, and build workflows on a canvas with live browsers and terminals. It uses your own models: OpenAI, Anthropic, Gemini, a ChatGPT subscription, any OpenAI-compatible server, or local models through Ollama.

This repository is where the public beta builds are published. The app's source is private.

## Download

Get the latest `Canoryn.dmg` from [Releases](https://github.com/procodeai/canoryn-releases/releases/latest), or download it directly: [Canoryn.dmg](https://github.com/procodeai/canoryn-releases/releases/latest/download/Canoryn.dmg). Each release also lists a SHA-256 checksum.

Once installed, Canoryn checks for updates itself.

## Install

1. Open the DMG and drag **Canoryn** into Applications.
2. Open Canoryn. From 0.6.2 the app is signed with a Developer ID and notarized by Apple, so it opens like any Mac app, with no warning to clear.

Still on 0.6.1 or older? Let it update itself from the in-app updater, or download the current version above.

## Requirements

- macOS 15.4 (Sequoia) or later. Canoryn 0.5.0 is the last version for macOS 14.
- Apple Silicon or Intel. Apple Silicon is recommended if you run local models.
- A model: an API key for a cloud provider, a ChatGPT subscription, or a local model through Ollama.

## What's new in 0.6.1

- **Sign in from the app** with a one-time code; an Account page shows you, your plan and this Mac. Everything except publishing works without an account.
- **Models has its own section.** Set up providers once; chat and every AI node pick from them.
- **The agent core is the default engine for chat.** It checks its own edits and has you review its plan first.
- **Math in documents:** `$…$` and `$$…$$` render as on GitHub, in the app, exports, PDFs and published pages.
- **Agents comment** on code and documents, and you can answer, edit or delete their threads.
- Claude and Gemini stream end to end, plus many fixes from 0.6.0.

Full notes: [Canoryn 0.6.1](https://github.com/procodeai/canoryn-releases/releases/tag/v0.6.1) · All versions: [changelog](https://canoryn.app/docs/changelog)

## Your data

Projects, documents, workflows and chats stay on your Mac, and API keys are kept in the macOS Keychain. Canoryn talks to the model provider you choose directly; with a local model the whole loop stays on your Mac. Nothing is published unless you publish it.

## Links

- Website: [canoryn.app](https://canoryn.app)
- Documentation: [canoryn.app/docs](https://canoryn.app/docs)
- Report a bug or request a feature: [canoryn-issues](https://github.com/procodeai/canoryn-issues/issues)
- Support: [support@procodeai.com](mailto:support@procodeai.com)
