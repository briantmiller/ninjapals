# Ninja Pals – iPad install

A PWA has to be served from an https web address before an iPad can install it.
The quickest free way:

1. Go to https://app.netlify.com/drop on a computer.
2. Drag this whole `ninja-pals` folder onto the page. Netlify gives you a link like
   `https://something.netlify.app`.
   (GitHub Pages works too: put these files in a repo and turn on Pages.)
3. On the iPad, open that link in **Safari**.
4. Tap the **Share** button, then **Add to Home Screen**, then **Add**.
5. Open Ninja Pals from the home screen. It runs full screen and works offline
   after the first launch.

Tip for little hands: turn on Guided Access (Settings > Accessibility > Guided Access)
to keep your child inside the game.

## How to play
- Arrows move, the blue button jumps, the big round button attacks (hold it to keep attacking).
- Tap a ninja face at the top to switch any time.
- When a ninja runs out of hearts, they go rest and the next ninja jumps in.
  The team keeps rotating forever, so there is no game over.
- Every 100 points: confetti and one heart back.

Files: index.html (the whole game), manifest.json, sw.js (offline cache), icons.
