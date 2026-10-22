# For Jeniesys — A Little Universe

A static romantic mini-site designed for GitHub Pages. No build step, npm install, backend, or API key is required.

## Pages
- `index.html` — welcome page and surprise entry
- `memories.html` — four-photo gallery with swipe, keyboard, arrows, dots, and a photo lightbox
- `quest.html` — five-step playful love quest; completion unlocks the video and gift
- `video.html` — video memory page using `our-video.mp4`
- `letter.html` — secret note and final letter gift

## Assets
Keep `images/photo1.jpg` through `images/photo4.jpg`, `music.mp3`, and `our-video.mp4` in the same locations as supplied. Paths are relative, so the site works on GitHub Pages project URLs.

## Features added
- Heart-clipped floating photo/video memories, with an on-page Hearts on/off control
- Four-photo gallery and image lightbox
- Keyboard and touch gallery navigation
- Scroll reading indicator and back-to-top control
- Reduced-motion support and improved accessible labels/focus states
- Better error feedback for missing media
- Responsive mobile layout and persistent love-quest unlock state

## Publish on GitHub Pages
1. Extract the ZIP.
2. Upload the contents of the `jeniesys-monthsary` folder into the repository root (not the outer folder itself).
3. Commit to the branch configured in Settings → Pages.
4. Open the published URL and hard-refresh (`Ctrl+Shift+R`) if old CSS or JavaScript is cached.

## Important browser behavior
- Background music cannot be forced to autoplay reliably. Use the Play music button; browsers require a user gesture.
- The quest state and floating-heart preference are saved in that browser's local storage. They are not shared across devices.
- This is a static site; it does not send messages or track another person's location.


## Latest polish
- Navigation between the five local pages uses same-site page transitions so the background music element keeps playing instead of restarting on every click.
- Browser back/forward navigation is supported for those transitions.
- The video chapter uses a more cinematic, personal introduction; setup-instruction copy has been removed from the visitor-facing page.
- Keep `our-video.mp4` in the project root to use the bundled video memory.
