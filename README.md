# scroll.ly by shyee

**A modern, feature-rich desktop automation tool for Windows**

scroll.ly provides both **auto-scrolling** and **auto-clicking** capabilities with a beautiful, intuitive **PyQt5 interface**. Designed for **power users**, **gamers**, and anyone needing to automate repetitive mouse actions with **precision and style**.

---

## ✨ Features

### 🚀 Auto Scroller

* **Adjustable Speed**: Scroll speed (scrolls/sec) from **1 to 100**
* **Modes**:

  * **Block** (bursty)
  * **Smooth** (continuous)
* **Direction**: Scroll **Up** or **Down**
* **Target Application**: Limit scrolling to a **specific window** or **current screen**

### 🖱️ Auto Clicker

* **Clicking Modes**:

  * **Randomize**: Click random locations on screen or in a region, with random intervals
  * **Multi-Target**: Record and replay a sequence of clicks

    * Playback Modes: **Sequence** or **All at Once**
  * **Single Target**: Click a specific location at set interval and pattern
* **Patterns**: Single, double, or triple click per target
* **Visualizer**: Live preview of click locations
* **Pick Location**: Grab precise mouse coordinates
* **Record Clicks**: Capture click sequences for Multi-Target mode (with floating STOP button)
* **Presets**: Save/load your favorite clicker setups
* **Anti-Detection**: Random delays + small mouse moves to avoid detection
* **Scheduling**: Schedule start/stop times (Single Target only)
* **Live Mouse Position**: Real-time mouse coordinate display

---

## 🛠 Installation

### ✅ Requirements

* Windows OS
* Python **3.7+**

### 📦 Python Dependencies

* `PyQt5`
* `pyautogui`
* `pynput`
* `pygetwindow`

### 💻 Install Dependencies

```bash
pip install pyqt5 pyautogui pynput pygetwindow
```

### ▶️ Run the App

```bash
python scrollly.py
```

---

## 🚦 Usage

### 🌀 Auto Scroller Tab

1. Set Speed: Use spin box for scroll speed.
2. Select Application: Choose window or use "Current screen".
3. Choose Mode: **Block** or **Smooth**
4. Set Direction: **Up** or **Down**
5. Click **Run** to start, **Stop** to halt.

### 🔁 Auto Clicker Tab

1. Select Application: Window or "Current screen".
2. Choose Preset or configure manually.
3. Select Clicking Mode:

   * **Randomize**: Set click speed & pattern.
   * **Multi-Target**:

     * Click **Record Clicks**, perform clicks, STOP.
     * Set playback mode & loop options.
   * **Single Target**:

     * Enter X/Y, interval, and pattern.
     * Optional: Set start/end schedule.
4. Enable **Anti-Detection** (optional).
5. Click **Run** to start, **Stop** to halt.
6. **Visualizer**: Live preview of clicks.

---

## 💾 Presets

* **Save Preset**: Click “Save Preset”, name it.
* **Load Preset**: Use dropdown to apply.
* **Delete Preset**: Remove unwanted setups.

---

## 🎬 Recording Clicks (Multi-Target)

1. Select **Multi-Target** mode.
2. Click **Record Clicks**.
3. Perform your clicks.
4. Click the **STOP** button in bottom left.
5. Configure playback options.

---

## 🎯 Picking Locations

Use **Pick Location** buttons to get current mouse coordinates.

---

## ⏰ Scheduling (Single Target)

Enable **Schedule Start** and/or **End** to run automation at specific times.

---

## 💡 Tips

* Use **Pick Location** for easy coordinate setup.
* Use **Record Clicks** in Multi-Target for complex sequences.
* Use **Presets** for quick switching.
* Ensure the target window is **active** and **not blocked** by overlays.

---

## ❓ FAQ

**Q:** The app isn’t working in my target window
**A:** Ensure the window is **active** and not covered. Some apps may block automation.

**Q:** How do I use Multi-Target?
**A:** Select mode → Click **Record Clicks** → Perform clicks → Click **Run**.

**Q:** How do I use Single Target?
**A:** Select mode → Set X/Y, interval, pattern → Click **Run**.

**Q:** How do I use Randomize?
**A:** Select mode → Set speed & pattern → Click **Run**.

---

## 📄 License

**scroll.ly** © 2024
All rights reserved.

---

## 🙌 Credits

* **UI/UX**: Modern dark theme with orange accent, inspired by popular design systems
* **Built with**:

  * PyQt5
  * pyautogui
  * pynput
  * pygetwindow

---

**Enjoy automating with scroll.ly!** ✨

---
