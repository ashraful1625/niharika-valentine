# 🌹 GitHub Publishing Guide — For Niharika's Website

## Files You Have
```
index.html       ← Landing page (start here)
dashboard.html   ← Main menu
valentine.html   ← All 8 Valentine week days
photos.html      ← Photo gallery with swipe
games.html       ← 3 love games
secret.html      ← Password-protected letter
```

---

## Step 1 — Upload to Your GitHub Repository

1. Go to **github.com** and open your repo:  
   `https://github.com/ashraful1625/niharika-valentine`

2. Click **"Add file"** → **"Upload files"**

3. Drag and drop ALL 6 HTML files into the upload area

4. Scroll down, write a commit message like: `Add full valentine website`

5. Click **"Commit changes"**

---

## Step 2 — Enable GitHub Pages

1. In your repo, click **"Settings"** (top tab)

2. In the left sidebar, click **"Pages"**

3. Under **"Source"**, select:  
   - Branch: `main`  
   - Folder: `/ (root)`

4. Click **Save**

5. Wait 1–2 minutes, then GitHub will show you a green banner with your live URL:  
   `https://ashraful1625.github.io/niharika-valentine/`

---

## Step 3 — Update Your Photo Links (Important!)

In `photos.html`, the photo URLs are already set to your GitHub repo.  
Make sure your photo files are in the **root** of your repo with these exact names:

```
IMG_20260405_230355.jpg (1).jpeg
IMG_20260405_230450.jpg (1).jpeg
IMG_20260405_230603.jpg (1).jpeg
IMG_20260405_230754.jpg (1).jpeg
```

If your photo file names are different, open `photos.html` and update the `url:` values in the `photos` array at the top of the `<script>` section.

---

## Step 4 — Test Your Website

Visit: `https://ashraful1625.github.io/niharika-valentine/`

Check each page:
- ✅ Landing page plays music on first tap
- ✅ Dashboard shows all 4 sections
- ✅ Valentine: tap each day → letter opens with animation
- ✅ Photos: swipe cards left/right, download button works
- ✅ Games: all 3 games playable
- ✅ Secret: password is `niharika` (lowercase)

---

## 🎵 Optional — Add Your Own Song

Replace the music source in ALL 6 HTML files.  
Find this line in each file:
```html
<source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mpeg">
```

Replace with your own song. The easiest way:
1. Upload your `.mp3` file to the GitHub repo (e.g., `song.mp3`)
2. Change the src to: `song.mp3`

---

## 💡 Tips

- The website is **fully mobile optimized** — share the link via WhatsApp
- The secret password is: **niharika** (all lowercase)
- Every page has a **← Dashboard** back button
- Music auto-plays on the first tap anywhere on each page
- Tapping anywhere creates floating hearts ❤️

---

*Made with love, by Aru — for Niharika 🌹*
