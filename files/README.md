# happy 1 year, baby 💗

A tiny anniversary site — floating hearts hero, an envelope that opens into your letter, flip cards for your "reasons I love you," and a photo gallery.

## Add your photos (2 min)
Drop up to 10 photos into the `photos` folder, named exactly:
```
photo1.jpg
photo2.jpg
...
photo10.jpg
```
Fewer than 10? No problem — any slot without a matching file just shows a soft pastel placeholder instead of breaking.
(If your files are `.png` instead of `.jpg`, open `index.html`, find the line `const src = \`photos/photo${i}.jpg\`;` and change `.jpg` to `.png`.)

## Edit the words (optional)
Everything text-wise lives in `index.html`:
- The letter text is inside the `<div class="letter" id="letterBox">` block.
- The 8 "reasons I love you" cards are in the `reasons` array near the bottom, in the `<script>` section — edit the `front`/`back` text or icons freely.
- The footer sign-off is in the `<footer>` block.

## Host it on GitHub Pages (10 min)
1. Create a new repository on GitHub (e.g. `for-baby` or `our-anniversary`) — Public.
2. Upload `index.html`, the `photos` folder (with your images inside), and this `README.md` — either drag-and-drop on the GitHub website, or:
   ```
   git init
   git add .
   git commit -m "happy anniversary"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. On GitHub, go to **Settings → Pages**.
4. Under "Build and deployment," set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)` → **Save**.
5. Wait ~1 minute, then your site is live at:
   `https://<your-username>.github.io/<repo-name>/`

Send him the link 💌
