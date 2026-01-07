# Spectator Zen for Twitch

Spectator Zen is a lightweight, free Chrome extension designed to improve the Twitch viewing experience by reducing visual distractions and helping viewers focus on the stream.

It provides a simple **Zen Mode** toggle that cleans up the layout using safe, robust CSS — with no tracking, no accounts, and no unnecessary complexity.

> This extension is not affiliated with or endorsed by Twitch.

---

## ✨ Features

- **Zen Mode ON / OFF**
  - Instantly switch between a normal and distraction-free layout.
- **Hide sidebar / recommendations**
  - Removes the left sidebar to reduce visual clutter.
- **Hide chat**
  - Optionally hides the chat panel for maximum focus.
- **Cinema width (best effort)**
  - Expands the player when Twitch applies width limits.
- **Page whitelist**
  - Zen Mode applies only to channel pages by default.
- **Experimental mode**
  - Optional support for Home / Directory pages.
- **Keyboard shortcuts**
  - `Alt + Z` → Toggle Zen Mode  
  - `Alt + Shift + O` → Open the extension popup

---

## 🧠 Design Philosophy

- One toggle = Zen experience
- Minimal permissions
- No analytics, no tracking, no login
- Fail-safe CSS (if a selector doesn’t exist, nothing breaks)
- Robust against Twitch layout changes
- Designed to feel native and unobtrusive

---

## 🧩 How It Works

The extension applies a global `zen-on` class to the page and uses conservative, container-level CSS selectors to hide or adjust layout elements.

A lightweight `MutationObserver` ensures Zen Mode persists across Twitch’s single-page navigation without aggressive DOM manipulation.

---

## 🧪 Compatibility

Spectator Zen is designed for **maximum compatibility across Chrome versions**:

- Fully compatible with **modern Chrome releases**
- Compatible with **older Chrome versions (around 2022)**, including many Chromebooks
- Built using **Manifest V3**
- No experimental JavaScript or CSS features
- No build tools or external dependencies

This approach ensures stable behavior on both newer and older systems.

---

## 🔐 Permissions

The extension only uses the minimum permissions required to function:

- `https://*.twitch.tv/*`
- `storage`
- `commands`

No additional access is requested.

---

## ☕ Support

If you enjoy calmer streams and want to support development:

**Buy Me a Coffee** → https://buymeacoffee.com/nightintel

Support is optional and never intrusive.

---

## 📜 License

This project is licensed under the **MIT License**.
