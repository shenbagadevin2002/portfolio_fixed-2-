# Your Portfolio Website — Ready to Deploy

## What's in this folder
- `index.html` — your complete portfolio website (one file, no build step needed)
- `assets/` — empty folder, ready for your images (see checklist below)

---

## How to host on Netlify (takes 2 minutes)

1. Go to **https://app.netlify.com**
2. Sign up / log in (you can use Google or GitHub)
3. On the dashboard, find the box that says **"Drag and drop your site output folder here"**
4. Drag the whole **`portfolio`** folder (the one containing `index.html`) into that box
5. Netlify will give you a live link instantly, like `https://random-name-123.netlify.app`
6. (Optional) Click **Site settings → Change site name** to make the link nicer, e.g. `shenbagadevi-seo.netlify.app`

That's it — your site is live.

---

## Details I need from you (send one by one or all at once)

To finish the site properly, please share:

1. **Profile photo** — a clear headshot (used in the About section if you want one added)
2. **Resume PDF** — so visitors can click "Download Resume" (right now it just shows a message)
3. **Screenshots** (this is the most important one):
   - Google Search Console keyword report
   - Before/after meta tags (Alisa Dental Care)
   - An SEO audit report sample
   - Schema markup code snippet (VS Code)
4. **Confirm these live links still work:**
   - http://ceramicgrindingmedia.com
   - http://paintsmart.in
5. **Brand color preference** — I used blue + black + green (Google-style). Let me know if you'd prefer a different main color.
6. **Domain name idea** (optional) — if you want something like `shenbagadevi-seo.netlify.app`, tell me the name you'd like.
7. **Certificate** — your SimplifyE-Learning SEO course certificate, if you want it shown as proof.

---

## How to add your screenshots once you have them

1. Save your screenshot images into the `assets` folder. Use these exact names:
   - `gsc-report.png`
   - `meta-before-after.png`
   - `audit-report.png`
   - `schema-snippet.png`
2. Open `index.html` in any text editor (or VS Code)
3. Find the matching placeholder box (search for the filename in a comment, e.g. `gsc-report.png`)
4. Delete the placeholder `<div class="sample-media">...</div>` text line
5. Remove the `<!-- -->` around the `<img>` tag just below it

**Example — before:**
```html
<div class="sample-media">[ Add screenshot: Search Console keyword report ]
  <!-- <img src="assets/gsc-report.png" alt="Google Search Console keyword report"> -->
</div>
```

**Example — after:**
```html
<div class="sample-media">
  <img src="assets/gsc-report.png" alt="Google Search Console keyword report" style="display:block;">
</div>
```

Send me the screenshots and I can do this step for you instead — just upload them in chat.
