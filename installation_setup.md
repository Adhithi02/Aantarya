# 🚀 Aantarya — Installation & Setup Guide

Welcome to **Aantarya** – a cultural bridge connecting locals and non-locals to the soul of **Bengaluru** through immersive digital experiences. This guide helps you get the project up and running on your machine and mobile device.

---

## 🧰 Prerequisites

Ensure you have the following installed:

- Node.js (v16 or later recommended)
- npm (comes with Node.js)
- Git (for cloning)
- A modern browser (like Chrome or Firefox)

---

## 📁 Step 1: Clone the Repository

```bash
git clone https://github.com/YourUsername/Aantarya.git
cd Aantarya
```

---

## 📂 Step 2: Open the Frontend Source Folder

Navigate into the React source code folder:

```bash
cd "Aantarya-main /Aantarya-main"

```

---

## 📦 Step 3: Install Dependencies

Install the required packages using npm:

```bash
npm install
```

---

## 🔧 Step 4: Start the Development Server

Launch the app locally:

```bash
npm run dev
```

Open the local link displayed in the terminal (usually http://localhost:5173) to view the app.

---

## 📱 Step 5: Run on Mobile Device (Same WiFi)

Want to test on your phone? Here's how:

### ✅ a. Get Your IP Address

On your computer, run:

- **Windows:** `ipconfig`
- **macOS/Linux:** `ifconfig`

Look for your **IPv4 address** (e.g., `192.168.0.102`).

### ✅ b. Update Vite Config

In `vite.config.js`, add:

```js
export default defineConfig({
  server: {
    host: true
  }
});
```

### ✅ c. Restart the Server

```bash
npm run dev
```

You’ll now see:

```
Local:   http://localhost:5173/
Network: http://192.168.0.102:5173/
```

### ✅ d. Open on Your Phone

- Connect your mobile to the **same WiFi network**.
- Open the **Network URL** (e.g., `http://192.168.0.102:5173/`) in your phone’s browser.

Boom! You’re now testing Aantarya on your mobile.

---

## 🧠 How to Use Aantarya

- **Locals**: Play cultural quizzes under “Places”, “Food”, “Traditions & Events”, “History”.
- **Non-Locals**: Access Kannada translation & pronunciation tools to ease communication.
- **Shared**: Explore iconic landmarks and eateries using AR and street view features.

---

## 🔍 Project Stack

- **React 18 + Vite**
- **Tailwind CSS** for styling
- **AR** and **Street View** integrations
- **TypeScript** + modular components
- **TTS (Text-to-Speech)** for Kannada pronunciation

---

## ✅ You're All Set!

Explore, interact, and enjoy discovering the cultural gems of Bengaluru through Aantarya. Let us know if you'd like to contribute or improve any feature! ❤️
