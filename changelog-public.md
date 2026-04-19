# 📱 FarmPhone | Development Update v0.2.0

> **A bridge between farming and the digital age.** > This update transforms the basic interface into a modular smartphone ecosystem, deeply integrated with Stardew Valley's classic aesthetic.

---

## 🚀 Key Milestones

### 🏠 The Launcher & App System
The phone now features a functional **Home Screen**. It’s no longer just a menu; it’s a platform.
- **Dynamic State Machine:** Seamlessly switch between `Home`, `Contacts`, and `Chat` states.
- **Custom Asset Injection:** Support for external `.png` sprites loaded via SMAPI.
- **Interactive UI:** Icons now feature hover effects and scaling for a premium "tech" feel.

### 🎨 Visual Overhaul (The "Cozy" Update)
We ditched the generic blue rectangles for a theme that feels at home in Pelican Town.
- **Texture Boxes:** Utilizing native `drawTextureBox` for perfect rounded corners.
- **Stardew Palette:** Implementation of the `Wheat`, `Gold`, and `DarkBrown` color scheme.
- **Improved UX:** Added a physical **Home Button** on the device frame to reset the state at any time.

---

## 📊 Comparison: Old vs. New

| Feature | Legacy v0.1 | Modern v0.2 |
| :--- | :--- | :--- |
| **Corner Style** | Sharp / Square | Rounded (Vanilla Aesthetic) |
| **Color Scheme** | High-Contrast Blue | Warm Wheat & Earthy Tones |
| **Hierarchy** | Static List | Multi-App Infrastructure |
| **Navigation** | Back Buttons only | Dedicated Home Button & App Icons |

---

## 🛠️ Technical Implementation
Bug Fixes & Stability
- **Layering**: Fixed the Status Bar (Time/Battery) overlapping with app content.
- **Safe Loading**: Implemented try-catch blocks and File.Exists checks to prevent crashes when assets are missing.
- **Input**: Recalibrated click bounds to match the new scaled UI elements.

📋 What's Next?
- [ ] Notification System: Visual and audio alerts for incoming messages.
- [ ] Interactive Replies: Player-choice dialogue trees.
- [ ] Time Delay: NPCs won't reply instantly—expect realistic typing delays!

Developed with ❤️ by Lander, for the Stardew Valley Modding Community.


---