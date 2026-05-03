# 📝 Spelling Master — 11+ Practice App

A drag-and-drop spelling practice app for 11+ exam preparation.
**No build step. No install. One file.**

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
