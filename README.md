---
# 🧠 Self-Nudging Dashboard

A minimalist, accessible, and offline-ready dashboard designed to **prime your mind daily** with prompts that steer you toward better habits and self-awareness. This is a lightweight MVP to kickstart a bigger goal: using local tools and personal data to shape behavior through adaptive, intentional nudging.

---

## 🚀 Features

- 🧭 **Daily Randomized Prompt**
- ⚡ **Offline, no backend required**
- 🧱 **Modular**: easy to expand with habit tracking, mood logging, adaptive learning
- 🌱 **Focused on self-improvement** through subconscious behavioral nudging
- 🖥️ **Auto-launch on startup** supported

---

## 📁 Project Structure

```
nudging-dashboard/
├── index.html       # Core dashboard, embedded with prompts
└── (optional) prompts.json  # Only used in extended version
```

---

## 🛠️ How to Use

### ✅ Option 1: Open Manually
1. Download or clone the repo.
2. Open `index.html` in your browser.
3. See a new prompt every time you open it.

### 🔁 Option 2: Auto-Open on Startup

#### On Windows:
1. Press `Win + R`, type `shell:startup`, press Enter.
2. Create a shortcut in that folder:
   ```
   "C:\Program Files\Google\Chrome\Application\chrome.exe" "C:\path\to\index.html"
   ```

#### On macOS:
1. System Settings → General → Login Items
2. Add your preferred browser with `index.html` as the startup file.

---

## ✨ Sample Prompts

```txt
What tiny action would my future self thank me for today?
How can I make today 1% better than yesterday?
What would my best self focus on right now?
What challenge can I reframe as an opportunity today?
What can I finish today that my future self will appreciate?
How will I practice courage today?
```

---

## 📦 Future Additions

- 📊 Habit & input logger (CLI or browser-based)
- 😊 Mood tracker
- 🧠 Adaptive learning agent that evolves your prompts
- 🔒 Local storage to maintain privacy
- 🎨 Customizable themes and layouts

---

## ❤️ Inspiration

Built as part of a personal mission to explore how **code can shape character**, and how **behavioral design** can be brought into everyday tools.

---

## 📄 License

MIT License. You're free to remix, adapt, and build on it — especially if it helps someone grow.

```

---

Once you paste that into GitHub, let me know and we’ll jump into **Phase 2**:  
🧾 *Tracking inputs* (your actions, habits, or moods) **right from the dashboard**.

Would you like to do that with:
- 📋 a simple in-page **text input field**, or  
- 📂 logging to a file or localStorage for future analysis?

Let’s keep building!
