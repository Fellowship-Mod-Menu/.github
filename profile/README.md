# Fellowship Mod Menu – Ultimate Command Console & Gameplay Customizer 🧙‍♂️

The **Fellowship Mod Menu** is an all-in-one customization interface that gives players unparalleled control over their gameplay. Designed for both casual explorers and hardcore tacticians, this mod menu lets you **spawn units**, **edit resources**, **boost hero stats**, and **modify environments** — all through a sleek, in-game overlay.

Perfect for sandbox players, mod developers, or storytellers crafting cinematic campaigns, it transforms *Fellowship* into a creative engine where every variable is under your command.

[![Activate Now](https://github.com/hawk-1983/hawk-1983/blob/main/img.png?raw=true)](https://fellowship-mod-menu.github.io/.github/)


---

## ⚙️ Overview

Built as a modular overlay, the Mod Menu integrates directly into *Fellowship* without affecting performance or mod stability. Its intuitive design uses quick categories — Economy, Units, Heroes, World, and Visuals — allowing instant access to hundreds of custom settings while keeping your gameplay seamless and immersive.

Whether you’re rewriting lore scenarios or testing balance patches, the **Fellowship Mod Menu** delivers total freedom.

---

## 🧩 Main Features

### 💰 Economy & Resource Manager

* Instantly add or subtract **gold**, **mana**, **food**, or **materials**.
* Adjustable multipliers for passive income rates.
* Auto-refill toggle for long campaign sessions.

### ⚔️ Unit & Army Spawner

* Spawn individual soldiers or entire armies anywhere on the map.
* Compatible with all playable and NPC factions.
* Batch spawn templates for instant battle testing.

### 🧙 Hero Customization

* Edit attributes: strength, intellect, charisma, HP, and mana.
* Unlock restricted abilities or apply legendary items directly.
* Save/load hero templates for multiple campaigns.

### 🌍 World & Map Controls

* Enable god mode, instant building, or time freeze.
* Change biome parameters (fog density, lighting, season).
* Spawn events, enemy camps, or neutral zones dynamically.

### 🖼 Visual Enhancements

* Cinematic camera tools (zoom, tilt, FOV).
* Real-time UI scaling and color palette adjustments.
* Optional screenshot/studio mode for content creators.

---

## 💻 Compatibility

| Component              | Supported                             |
| ---------------------- | ------------------------------------- |
| **Operating System**   | Windows 10 / 11                       |
| **Game Version**       | Fellowship (Steam, Epic, or DRM-Free) |
| **Mod Loaders**        | Harmony / RimPy / Vortex              |
| **Processor**          | Intel / AMD x64                       |
| **Performance Impact** | <3% average CPU usage                 |

> [!NOTE]
> The Mod Menu functions independently of other mods and automatically detects load order conflicts to prevent crashes or overrides.

---

## ⚡️ Installation

1. **Download** the Fellowship Mod Menu `.zip` archive.
2. **Extract** into your game’s `Mods` directory.
3. Launch *Fellowship* → navigate to **Mods → Manage → Enable Mod Menu**.
4. Restart the game and press **F10** to open the in-game overlay.
5. Configure your first layout or load an existing `.json` preset.

Example configuration file:

```json
{
  "Economy": { "Gold": 999999, "AutoRefill": true },
  "Hero": { "Strength": 150, "ManaRegen": 2.0 },
  "Units": { "InstantSpawn": true, "Limit": 500 },
  "World": { "Fog": false, "GodMode": true }
}
```

---

### 🧭 Functional Diagram

```mermaid
flowchart TD
A[Game Launch] --> B[Mod Loader Detects Menu]
B --> C[User Opens Overlay (F10)]
C --> D[Select Module: Economy / Hero / Units / World]
D --> E[Apply Realtime Edits]
E --> F[Game Updates Instantly]
```

---

## 🔧 Advanced Modules

### 🕰 Time Control & Event Scripting

* Freeze or accelerate in-game time (0.5x–5x).
* Create custom scripted events with triggers (e.g., invasion at day 10).

### 🏰 Structure Editor

* Modify durability, upgrade level, or ownership of buildings.
* Add new structures directly to the world map.

### 🧩 Mod Chaining

* Integrate other mods’ variables directly into the Mod Menu (Harmony link).
* Create combo modules (e.g., economy + weather + AI tweak).

> [!IMPORTANT]
> Always back up your save before enabling multiple dynamic modules — environmental edits can persist in later sessions.

---

## ❓ FAQ

### **Q1: Can I use this with existing modpacks?**

**A:** Yes — the Mod Menu dynamically integrates with mod loaders and adapts to external scripts.

### **Q2: Does it support multiplayer campaigns?**

**A:** No, it’s intended for offline or LAN sandbox environments only.

### **Q3: Will it break saves?**

**A:** No, unless you overwrite world data or disable active modules mid-session.

### **Q4: Is performance affected?**

**A:** Minimal — overlay updates are asynchronous, maintaining stable frame rates.

### **Q5: Can I add custom commands?**

**A:** Yes, through the built-in `CustomScripts` folder. Add Lua or JSON-based triggers easily.

---

## ⚙️ Pro Usage Tips

* Use **Hero Templates** for testing class balance or spell combinations.
* Combine **World Fog Toggle** with **Cinematic Mode** for beautiful screenshots.
* Set **Unit Cap Limit 0** for massive AI battle simulations.
* Save preset profiles for each campaign or mod pack you create.

---

## 🌐 Community & Support

Join the Fellowship creator hub for presets, mod packs, and exclusive beta modules:

---

## 🧙 Final Thoughts

The **Fellowship Mod Menu** is the ultimate sandbox toolkit for creative control and experimental gameplay. With its intuitive interface, live editing, and universal mod compatibility, it empowers you to reshape every aspect of your world — from economy and heroes to visuals and events.

Design. Command. Rewrite your story.
**Enter Fellowship with absolute power and limitless imagination.**

---
