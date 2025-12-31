# XToLevel - Project Ascension Compatibility Patches

[![Release](https://img.shields.io/github/v/release/Xurkon/PA-XtoLevel?style=for-the-badge&color=e67e22)](https://github.com/Xurkon/PA-XtoLevel/releases)
[![Downloads](https://img.shields.io/github/downloads/Xurkon/PA-XtoLevel/total?style=for-the-badge&color=e67e22)](https://github.com/Xurkon/PA-XtoLevel/releases)
[![Interface](https://img.shields.io/badge/Interface-3.3.5a-blue?style=for-the-badge)](https://github.com/Xurkon/PA-XtoLevel)
[![Documentation](https://img.shields.io/badge/Documentation-View%20Docs-58a6ff?style=for-the-badge)](https://xurkon.github.io/PA-XtoLevel/)
[![Patreon](https://img.shields.io/badge/Patreon-F96854?style=for-the-badge&logo=patreon&logoColor=white)](https://www.patreon.com/Xurkon)
[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://www.paypal.me/Xurkon)

A patched version of the classic **XToLevel** addon, specifically optimized for the **Project Ascension** (3.3.5a) client.

## 🚀 Overview

XToLevel shows exactly how many mobs, quests, dungeons, and battlegrounds you need to reach your next level. This version includes critical fixes for pet-related Lua errors that occur on the Ascension client.

### ✨ Key Fixes in v3.3.5_15r-PA
- **Fixed Pet XP Lua Error:** Resolved the `table index is nil` error in `Pet.lua` that triggered during pet XP gains.
- **Improved Guard Logic:** Added safety checks to ensure pet data is correctly indexed even during summoning/dismissing transitions.
- **Project Ascension Optimization:** Tailored for the Bronzebeard - Warcraft Reborn environment.

## 📥 Installation

1. Download the [latest release](https://github.com/Xurkon/PA-XtoLevel/releases).
2. Extract the `XToLevel` folder into your World of Warcraft directory:
   `Interface/AddOns/`
3. Ensure "Load Out of Date Addons" is checked in your addon list (though this version is updated for 3.3.5).

## 🛠 Features
- **Estimated Kills/Quests:** Predictive leveling based on your recent activity.
- **Blocky & Classic Views:** Choose between a modern graphical display or a classic text-based frame.
- **LDB Support:** Compatible with TitanPanel, ChocolateBar, and other LibDataBroker displays.
- **Pet Support:** (Now Fixed!) Track your hunter pet's progress alongside your own.

## 📄 Documentation
Detailed technical changes and documentation can be found in the [docs](https://xurkon.github.io/PA-XtoLevel/docs/index.html) page (if hosted) or locally in:
- `CHANGELOG.md`
- `docs/index.html`

## 🤝 Credits
- **Original Author:** Atli Þór
- **Ascension Fixes:** Xurkon

---
*Maintained by Xurkon for the Ascension Community.*
