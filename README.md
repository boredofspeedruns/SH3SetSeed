# SH3 Set Seed
### Silent Hill 3 — RNG & Enhancement Mod

**SH3SS** introduces deterministic puzzle solutions, critical bug fixes, and a real-time HUD designed for speedrun verification and technical stability.

---

## 🚀 Key Features

### 🧩 Gameplay & RNG
* **Deterministic Seeds:** Forces randomized puzzles to use consistent, pre-defined codes (see the [Solutions table](#-fixed-puzzle-solutions)).
* **10-Star Bonuses:** The **Beam Saber** and **Flamethrower** upgrades are now permanent once unlocked, even after completing non 10-star runs.
* **IGT Bug Fix:** Resolves the notorious **Supply Key In-Game Timer (IGT) bug**.

### 🖥️ Technical & Visual
* **Real-Time HUD Overlay:** On-screen timer for speedrun verification and timing accuracy.
* **Widescreen Support:** Includes ThirteenAG's widescreen patch, configurable via `.ini`.
* **Options Fix:** Automatically applies the "Options Fix" for fresh installs when the main mod is enabled.
* **Independent Toggles:** IGT Fix and Timer Display can be run independently of the seed features.

### 🛠️ Developer Tools
* **Experimental Debug Mode:** Toggle **Freecam** using `F9`.

---

## 🛠 Installation & Usage

1.  **Extract Files:** Copy `d3d8.dll` and `sh3setseed.ini` into your main **SILENT HILL 3** installation directory.
2.  **Configuration:** Open `sh3setseed.ini` to toggle features (ensure `enabled=1` is set for the main suite).
3.  **Launch:** Start the game; the mod and overlay will load automatically.

---

## 🧩 Fixed Puzzle Solutions
When the mod is active, the following codes are forced for randomized puzzles. 

> [!NOTE]
> Puzzles with hard-coded logic based on difficulty (e.g., Hard difficulty Shakespeare Bookstore or Crematorium) remain unchanged from their original game behavior.

| Difficulty | Bookstore | Hospital Keypad | Hospital Clock | Crematorium |
| :--- | :--- | :--- | :--- | :--- |
| **Easy** | `2580` | `2589` | `0100` | *N/A* |
| **Normal** | `2580` | `2589` | `0100` | `7012` |
| **Hard** | `8352` | `2589` | `1200` | `9271` |

---

## 📸 Freecam Controls
*Activate by toggling `F9` in Debug Mode.*

| Movement | Keys |
| :--- | :--- |
| **X-Axis** | `Up` / `Down` Arrow |
| **Y-Axis** | `Left` / `Right` Arrow |
| **Z-Axis** | `[` / `]` |
| **Yaw** | `.` / `/` |
| **Pitch** | `;` / `'` |

---

## ⚖️ Disclaimer
> [!IMPORTANT]  
> This is a fan-made reverse-engineering project. It is not affiliated with, maintained by, or endorsed by Konami. Use this software at your own risk.
