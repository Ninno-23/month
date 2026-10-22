# For Jeniesys ♡ — A Little Universe

A personal multi-page monthsary site with photos, a playful love quest, couple video, floating hearts, background music, and a gift letter.

## What’s included

| File / Folder | Purpose |
|---------------|---------|
| `index.html` | Home / opening |
| `memories.html` | Photo gallery (3 photos) |
| `quest.html` | 5-question interactive love game |
| `video.html` | Couple video (unlocks after quest) |
| `letter.html` | Secret note + gift-box love letter |
| `style.css` | Shared styles |
| `app.js` | All interactivity + floating hearts + music |
| `our-video.mp4` | Couple video |
| `music.mp3` | Background song (Sheryl Cruz – Ikaw Ang True Love Ko) |
| `images/` | photo1.jpg, photo2.jpg, photo3.jpg, photo4.jpg |

## How to put on GitHub + GitHub Pages (no errors)

1. Create a **new repository** on GitHub (public is easiest for Pages).
2. Upload **everything inside this folder** (all HTML, CSS, JS, `music.mp3`, `our-video.mp4`, and the `images/` folder).  
   Do **not** put an extra outer folder — the files should be at the root of the repo.
3. Go to **Settings → Pages**.
4. Under **Source** choose:
   - Deploy from a branch → `main` (or `master`) → `/ (root)`
5. Click **Save**.
6. Wait 1–2 minutes. Your site will be live at:
   ```
   https://YOUR-USERNAME.github.io/REPO-NAME/
   ```

### Important notes so it works without errors

- All paths are **relative** (`images/photo1.jpg`, `music.mp3`, `our-video.mp4`) — works on GitHub Pages.
- File names are exact: `music.mp3` and `our-video.mp4` (no spaces or special characters).
- The love quest progress is saved in the browser’s `localStorage`.
- Music starts after the first click (browser autoplay rules). There is a ♪ button on every page to pause/play.
- Complete the Love Quest to unlock the video page and the gift letter.

## Test locally first (optional)

```bash
# From this folder
npx serve .
# or just open index.html in a browser
```

Made with all my heart for Jeniesys ♡
