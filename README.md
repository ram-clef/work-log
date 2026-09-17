# Work Log

A minimalist PWA for tracking daily work hours, sending quick WhatsApp updates to your team, and visualizing your work history with charts.

**Designed & Developed by Pruthvi raj**

---

## 🌐 Live App

**https://ram-clef.github.io/work-log/**

Install it on your phone's home screen and it works like a native app — full-screen, own icon, offline capable.

---

## ✨ Features

- **Daily work tracker** — Log in, lunch break, back to work, logout with one tap
- **WhatsApp quick-send** — Send pre-configured messages to your WhatsApp group without typing
- **Live timer** — Circular progress ring shows your daily progress in real time
- **Dashboard analytics** — Success rate, best/worst days, overworked count, and more
- **5 charts** — Daily hours bar chart, trend line chart, weekday averages, 12-week heatmap, completion donut
- **XLSX export** — Download your full timesheet as an Excel file
- **Native notifications** — Lunch reminder, back-to-work reminder, logout reminder
- **10 accent colours + 10 fonts** — Personalize the look
- **Light & dark theme** — Auto-detects system preference
- **100% offline** — Data stays on your device (localStorage). No servers, no accounts.

---

## 📱 How to install as an app

### Android (Chrome)

1. Open **https://ram-clef.github.io/work-log/** in Chrome
2. Tap the **⋮** menu (top-right)
3. Tap **Install app** or **Add to Home screen**
4. Confirm → the Work Log icon appears on your home screen
5. Launch it — it opens full-screen, no browser bars

### iPhone / iPad (Safari)

1. Open **https://ram-clef.github.io/work-log/** in **Safari**
2. Tap the **Share** button (square with an up-arrow)
3. Scroll down and tap **Add to Home Screen**
4. Tap **Add** → the Work Log icon appears on your home screen

**Important:** iOS only allows installation from Safari. Chrome on iOS cannot install PWAs.

### Desktop (Chrome / Edge)

1. Open **https://ram-clef.github.io/work-log/**
2. Look for the **install icon** (⊕ or a monitor with an arrow) on the right side of the address bar
3. Click **Install** → it opens in its own window
4. Pin it to your taskbar/dock

### In-app help

The app also has an in-app **❓ help button** on every screen (Login, Work, Dashboard, Settings) with the same steps, tabbed by device type. In Settings, you can also tap **📲 Install now** if your browser supports the native install prompt.

---

## 🛠 Tech Stack

- **HTML/CSS/JS** — single-file app, no build step
- **Service Worker** — offline caching and native notifications
- **Web App Manifest** — installability as PWA
- **SheetJS** — XLSX export
- **localStorage** — data persistence (per device)

---

## 📂 Project Structure
