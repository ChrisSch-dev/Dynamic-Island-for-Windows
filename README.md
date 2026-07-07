# Dynamic Island for Windows

A fluid, living overlay inspired by Apple's Dynamic Island, bringing a beautiful, highly-responsive UI to your Windows desktop. Built natively with hardware-accelerated Direct2D rendering for a buttery-smooth 60 FPS experience.

![Dynamic Island Preview](https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/Full-preview.png)

---

## 🚀 Modules & Dashboards

The Dynamic Island intelligently expands to display context-aware dashboards. You can easily navigate between different views using your mouse scroll wheel.

| Module | Description | Preview |
| :--- | :--- | :--- |
| **Media Player** | Shows live album art, track details, audio waveforms, and full playback controls. | ![Media](https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/media.png) |
| **Calendar** | A sleek, perfectly aligned monthly calendar that highlights the current date. | ![Calendar](https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/calender.png) |
| **Weather** | Real-time weather stats powered by wttr.in, including wind speed, humidity, and "feels like" temperature. | ![Weather](https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/weather.png) |
| **Game Overlay** | Real-time FPS, CPU, GPU, and RAM utilization overlays tailored for gamers. | ![Gamebar](https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/gamebar.png) |
| **Idle View** | A minimal dashboard with your battery status, digital clock, and sleek pagination dots. | ![Idle](https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/idle.png) |
| **Camera Privacy** | Shows a green dot when an app is actively using your webcam. | ![Camera](https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/camera-detected.png) |
| **Mic Privacy** | Shows an orange dot when an app is actively using your microphone. | ![Mic](https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/mic-detected.png) |

---

## ✨ Core Features

- **Hardware Privacy Indicators:** A pulsing orange dot appears when your microphone is active, and a green dot when your camera is in use. Rate-limited polling ensures absolutely no CPU drain.
- **High-Res Clipboard & Notifications:** Instantly see what you copied or your latest Windows notifications, featuring crisp, high-fidelity 64px app icons extracted directly from system executables.
- **Dynamic Fluid Animations:** Fully smooth resizing and splitting when multiple events happen at once (e.g., media playing while you copy text or receive a notification).
- **Customizable Aesthetics:** Switch between sleek OLED Black, Dark Gray, Midnight Blue, and Deep Purple themes from the right-click menu, or use the settings to dial in your exact hex colors.

---

## ⚙️ Usage & Settings

- **Hover & Scroll:** Hover over the island to seamlessly expand it. Use your mouse scroll wheel to swipe between the Media, Calendar, and Weather tabs.
- **Right-Click Menu:** Right-click the island to access Theme presets, Transparency settings, and to pin the island open.
- **Windhawk Settings:** Visit the Mod Settings tab to change the island's Position, Size Scale, Animation Speed, and toggle specific modules. You can also perfectly align the island using the new `Offset X` and `Offset Y` settings, and even select exactly which monitor the island should appear on (including a brand new "Follow Mouse" mode!).
- **Notifications:** To use the notification module, you need to add `explorer.exe` to the process inclusion list in the Advanced tab of the mod settings and restart the mod.

---

## Fixes by ChrisSch-dev
- **Unintended Hover Expansion:** Fixed the unintended Hover Expansion for the GameMetrics Dynamic Island;
- **Text Wrapping:** Implemented text wrapping for Weather Description on Weather Dynamic Island, the weather description will no longer warp into the Info Section;
- **Maintain After Exit:** Fixed a problem where the page of the Dynamic Island wasn't reverted back to 0 after exitting the expanded Dynamic Island.
- **Weather Dashboard:** Fixed a problem where the Weather Dashboard fails to update after waking up the computer from Sleep Mode.
- **Memory Leaks:** Fixes various Memory Leak problems the original one has.

---

## 📝 Feedback & Credits

### Feedback / Support / Bug Reports
- Please use [Windhawk Mods Issues](https://github.com/ramensoftware/windhawk-mods/issues) or [dynamic-island-for-windows issues](https://github.com/devcode90/dynamic-island-for-windows/issues) to report bugs, request features, or share feedback.
- Clear descriptions, screenshots, or steps to reproduce help improve fixes and updates.
- Suggestions for UI/UX or new integrations are always welcome.

### Credits
- **[ciizerr @GitHub](https://github.com/ciizerr)**: Improved the UI by refining layout alignment, fixing dashboard scaling, and enhancing calendar and weather module integration.

