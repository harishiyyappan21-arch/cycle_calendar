# 🌙 Luna — Cycle Calendar

A beautiful, private menstrual cycle tracker that installs as an app on your phone.
**No accounts. No server. All data stays on your device.**

---

## 📁 Files in this zip

```
index.html      ← Main app (open this directly in browser too)
manifest.json   ← PWA config
sw.js           ← Offline service worker
icons/
  icon-192.png
  icon-512.png
README.md
```

---

## 🚀 Deploy to GitHub Pages (Free — takes 5 minutes)

### 1. Create a GitHub account
→ https://github.com/signup (free)

### 2. Create a new repository
- Click **+** → **New repository**
- Name: `luna-cycle` (or anything)
- Visibility: **Public**
- Click **Create repository**

### 3. Upload files
- On the new repo page click **"uploading an existing file"**
- Drag & drop **all files** (index.html, manifest.json, sw.js, icons folder)
- Click **Commit changes**

### 4. Enable GitHub Pages
- Go to **Settings** → **Pages**
- Source: **Deploy from a branch**
- Branch: **main** → **/ (root)**
- Click **Save**

### 5. Your app URL (ready in ~60 seconds)
```
https://YOUR-USERNAME.github.io/luna-cycle/
```

---

## 📱 Install on Your Phone

### Android (Chrome)
1. Open your GitHub Pages URL in **Chrome**
2. Tap **⋮ menu** → **Add to Home Screen** → **Install**

### iPhone (Safari — MUST use Safari)
1. Open your URL in **Safari** (not Chrome)
2. Tap the **Share button** ↑
3. Scroll → **Add to Home Screen** → **Add**

Luna will appear on your home screen like a native app and works offline!

---

## 🔒 Privacy
Everything is stored locally on your device using `localStorage`.
Use **Export → Backup JSON** to save your data before clearing your browser.
