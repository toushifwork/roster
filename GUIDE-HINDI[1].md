# Duty Roster ko Website/App banane ki Guide

Is folder me 5 files hain — **paancho** upload karni hain:

| File | Kaam |
|---|---|
| `index.html` | Pura roster app |
| `manifest.json` | App ka naam/icon (Add to Home Screen ke liye) |
| `sw.js` | Offline support |
| `icon-192.png`, `icon-512.png` | App ka icon |

---

## Step 1: GitHub account banao (free, 2 minute)

1. Phone/computer par kholo: **github.com/signup**
2. Email, password, username daalo (username yaad rakhna — link me aayega)
3. Verify karke account ban jayega

## Step 2: Repository banao

1. Login karke upar **+** button → **New repository**
2. Repository name: `roster` likho
3. **Public** select karo (zaroori hai, free Pages ke liye)
4. **Create repository** dabao

## Step 3: Files upload karo

1. Nayi repository ke page par **"uploading an existing file"** link dabao
   (ya `Add file → Upload files`)
2. Is folder ki **paancho files** drag karke daalo (ya choose files se select karo)
3. Niche **Commit changes** dabao

## Step 4: Website chalu karo (GitHub Pages)

1. Repository me upar **Settings** tab
2. Baaye side me **Pages**
3. "Branch" me **main** select karo, folder **/ (root)**, **Save**
4. 1-2 minute ruko, phir wahi page refresh karo — upar link dikhega:

   **`https://<tumhara-username>.github.io/roster/`**

Bas! Ye link sabko WhatsApp kar do.

## Step 5: Phone me app ki tarah lagao

1. Link ko **Chrome** me kholo
2. Menu (⋮) → **"Add to Home Screen"** / **"Install app"**
3. Home screen par **Duty Roster icon** aa jayega — app ki tarah khulega, **offline bhi chalega**

## Step 6: Purana data le aao (sirf ek baar)

> ⚠️ Nayi website ka data alag jagah hota hai, isliye:

1. **Purani HTML file** wale app me: menu ⋮ → **Backup Save Karein** → JSON file download
2. **Nayi website** kholo → "⬆️ Purana Backup Restore Karein" → wahi JSON file chuno
3. Sab data aa jayega. Ab purani HTML file ki zaroorat nahi.

---

## Aage update kaise hoga?

Jab bhi app me naya feature aaye:
1. Nayi `index.html` GitHub repository me upload karo (purani ke upar — "Upload files" se replace ho jati hai)
2. **Sab phones par apne aap naya version aa jayega** — kisi ko file bhejne ki zaroorat nahi!

## APK banana hai? (optional)

Website chalu hone ke baad:
1. **pwabuilder.com** kholo
2. Apna link daalo (`https://<username>.github.io/roster/`) → **Start**
3. **Android** → **Generate Package** → APK download
4. Ye APK phone me install ho jayega (Settings me "Install unknown apps" allow karna padega)

> Note: Zyada tar cases me PWA (Step 5) hi kaafi hai — APK ka fayda bas itna ki wo Play Store jaisi asli app lagti hai.

## Dhyan rakhne wali baatein

- Data ab bhi **har phone me alag** rehta hai (website sirf app deti hai, data sync nahi karti)
- Manager change ho to wahi purana tarika: **Backup JSON → WhatsApp → Restore**
- Backup reminder app me bana hua hai — 7 din me yaad dila dega
