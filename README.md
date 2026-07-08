# 🏝️ Dynamic Island for Windows

A smooth, interactive overlay for your desktop, inspired by Apple's Dynamic Island. It brings a sleek media widget, notifications, and system alerts to Windows without slowing down your PC.

---

## 📸 See it in Action

<p align="center">
  <img src="https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/Full-preview.png" alt="Dynamic Island Preview" width="600" style="border-radius: 8px; margin: 10px;"/>
</p>

### Dashboards

| Media Player | Calendar | Weather | Game Overlay | Idle View |
| :---: | :---: | :---: | :---: | :---: |
| <img src="https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/media.png" width="200" /> | <img src="https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/calender.png" width="200" /> | <img src="https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/weather.png" width="200" /> | <img src="https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/gamebar.png" width="200" /> | <img src="https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/idle.png" width="200" /> |

### Privacy Indicators

| Camera Detected | Microphone Detected |
| :---: | :---: |
| <img src="https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/camera-detected.png" width="200" /> | <img src="https://raw.githubusercontent.com/devcode90/Dynamic-Island-for-Windows/main/previews/mic-detected.png" width="200" /> |

---

## ✨ What it does

- 🟢 **Privacy Dots:** See an orange dot when your mic is on and a green dot for your camera.
- 🎵 **Media Player:** Live album art, audio waveforms, and playback controls.
- 📅 **Dashboards:** Scroll your mouse wheel to easily switch between Media, Calendar, and live Weather (via wttr.in).
- 🔒 **Key Alerts:** Get quick visual popups when you hit Caps Lock or Num Lock.
- 🔋 **Battery & Power:** Fluid animations when you plug in, unplug, or hit low battery.
- 🔌 **Device Status:** Alerts when you plug in a USB drive or connect a Bluetooth device.
- 🎢 **Bouncy Animations:** Enjoy satisfying spring physics that pop open and smoothly glide back.
- 🖥️ **Windows 11 Style:** Swap to a modern Fluent design with sleek borders and acrylic backgrounds.
- 📊 **Game Overlay:** Real-time FPS, CPU, GPU, and RAM stats built right in.
- 📋 **Clipboard & Notifications:** Instantly preview what you just copied or see your latest Windows notifications.
- 🎨 **Themes:** Pick from OLED Black, Midnight Blue, Deep Purple, or pick your own hex color.

---

## ⚙️ Customization

Tweak the mod easily from the **Windhawk settings panel**:
- **Position:** Place it Top Center, Top Left, Top Right, or Bottom Center.
- **Scale:** Shrink or enlarge it to fit your screen perfectly.
- **Style:** Choose the classic iPhone Pill look or the modern Windows 11 Fluent flyout.
- **Colors:** Match it to your album art automatically, use system colors, or pick your own.
- **Speed:** Set animations to Slow, Normal, or Fast.
- **Modules:** Turn on or off the parts you want (Media, Clipboard, Battery, etc.).
- **Process Inclusion (for Notifications):** To use the notification module, you must add `explorer.exe` to the process inclusion list under the **Advanced** tab of the mod settings in Windhawk, then restart the mod.

---

## Fixes by ChrisSch-dev
- **Unintended Hover Expansion:** Fixed the unintended Hover Expansion for the GameMetrics Dynamic Island ([v1.0.0](https://github.com/ChrisSch-dev/Dynamic-Island-for-Windows/releases/tag/v1.0.0))
- **Text Wrapping:** Implemented text wrapping for Weather Description on Weather Dynamic Island, the weather description will no longer warp into the Info Section ([v1.0.0](https://github.com/ChrisSch-dev/Dynamic-Island-for-Windows/releases/tag/v1.0.0)) 
- **Maintain After Exit:** Fixed a problem where the page of the Dynamic Island wasn't reverted back to 0 after exitting the expanded Dynamic Island. ([v1.0.0](https://github.com/ChrisSch-dev/Dynamic-Island-for-Windows/releases/tag/v1.0.0))
- **Weather Dashboard:** Fixed a problem where the Weather Dashboard fails to update after waking up the computer from Sleep Mode. ([v1.0.0](https://github.com/ChrisSch-dev/Dynamic-Island-for-Windows/releases/tag/v1.0.0))
- **Memory Leaks:** Fixes various Memory Leak problems the original one has. ([v1.0.0](https://github.com/ChrisSch-dev/Dynamic-Island-for-Windows/releases/tag/v1.0.0))
- **Unintended Movement:** Fixed unintended movement of the Dynamic Island when Volume Changes are detected ([v1.0.1](https://github.com/ChrisSch-dev/Dynamic-Island-for-Windows/releases/tag/v1.0.1))
- **Improved Performance:** Improved overall performance of the Dynamic Island ([v1.0.1](https://github.com/ChrisSch-dev/Dynamic-Island-for-Windows/releases/tag/v1.0.1), check Release Tab for details)
---

## 💬 Let's Chat!

Found a bug? Have a cool feature idea? We want to hear from you! Please drop an issue on our [GitHub Repository](https://github.com/ChrisSch-dev/Dynamic-Island-for-Windows/issues). Your feedback keeps this mod alive.

---

## 🙌 Shoutouts

- **[devcode90](https://github.com/devcode90):** The original developer for Dynamic Island on Windows - Click [here](https://github.com/devcode90/Dynamic-Island-for-Windows) for the original repository
- **[ciizerr](https://github.com/ciizerr)**: Massive thanks for fixing UI alignments, smoothing out the dashboard sizing, and polishing the calendar and weather tabs.

---

## 🛠️ Nerd Stuff

Built with C++23 and deeply integrated with Windows for maximum performance:
- **Direct2D:** Hardware-accelerated rendering for buttery 60 FPS animations.
- **Zero Lag:** Rate-limited polling and efficient system hooks mean it uses almost 0% CPU in the background.

---

## 📜 License

This project uses the [MIT License](LICENSE). Feel free to build on it!
