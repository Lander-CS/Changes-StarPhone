# 📱 Digital Era | Development Update v0.3.0

> **Enhanced Immersion & Classic Aesthetics.**
> This update brings the phone closer to the Stardew Valley spirit with a vanilla-inspired redesign and several quality-of-life improvements.

---

## ✨ What’s New

### 🎨 "Vanilla" Redesign
Goodbye dark, modern colors! The phone now uses the game's classic color palette (**beige and brown**), with message bubbles that look like little pieces of parchment. It finally feels like an item your farmer would actually carry!

### 🖱️ Scrolling System
Contact list getting too long? No problem. The menu now has full **mouse wheel support** and visual clipping to keep everything neat and tidy.

### 🔓 Auto-Unlock Contacts
Some NPCs can now come pre-installed on your phone! I’ve set it up so key characters (like **Mayor Lewis** or **Robin**) can text you a "Welcome" message and unlock their contact as soon as you start your journey.

### 🔔 Discreet Notifications
We’ve replaced the giant mid-screen alerts with subtle **HUD notifications** in the corner (quest-style). Less interruption, more immersion!

---

## 🛠️ Stability Fixes

- **Fully 1.6 Compatible:** Fixed the data loading error that caused crashes on new saves.
- **No More Ghost Messages:** Fixed a bug where notifications appeared twice or chats remained empty. Every message is now unique and correctly saved to your progress.

---

# 📱 Digital Era | Development Update v0.2.0

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