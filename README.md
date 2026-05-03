# 📝 Spelling Master — 11+ Practice App

A drag-and-drop spelling practice app for 11+ exam preparation.
**No build step. No install. One file.**

---

## 🚀 Deploy to GitHub Pages (5 minutes)

### Step 1 — Create a repository
1. Go to [github.com](https://github.com) and click **New repository**
2. Name it `spelling-master` (or anything you like)
3. Set it to **Public**
4. Click **Create repository**

### Step 2 — Upload the file
1. Click **Add file → Upload files**
2. Drag `index.html` into the upload area
3. Click **Commit changes**

### Step 3 — Enable GitHub Pages
1. Go to your repository → **Settings** → **Pages** (left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Choose branch: `main` · folder: `/ (root)`
4. Click **Save**

### Step 4 — Open your app
After about 60 seconds, your app will be live at:
```
https://YOUR-USERNAME.github.io/spelling-master/
```

---

## 💾 How history is saved

History is saved to the browser's **localStorage** on the user's device.
- ✅ Persists across page refreshes and browser restarts
- ✅ Private to each device — no server, no account needed
- ✅ Users can clear it any time from the History tab
- ⚠️ If the user clears browser data / site data, history is erased
- ⚠️ History does not sync between devices

---

## 📱 Works on

| Platform | Notes |
|---|---|
| Desktop (Chrome, Edge, Firefox, Safari) | Full drag support |
| iPad / iPhone | Touch-drag supported |
| Android tablet / phone | Touch-drag supported |

---

## 🔧 Customising words

Open `index.html` in any text editor and find the `GROUPS` array near the top of the `<script>` block. Each group has a `words` array — edit freely:

```js
{ id:0, name:"Tricky Double Letters", icon:"✌️", color:"#FF6B6B",
  words:["accommodation","committee", /* ... add or remove words here */ ] },
```

Save and re-upload to GitHub — changes are live instantly.

---

## 🏗 Tech stack

| Library | Version | Purpose |
|---|---|---|
| React | 18 | UI framework |
| ReactDOM | 18 | DOM rendering |
| Recharts | 2.12 | Progress trend chart |
| Babel Standalone | latest | JSX in-browser transform |

All loaded from **unpkg CDN** — no npm, no Node.js required.
