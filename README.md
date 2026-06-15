# The Penalty Oracle ⚽

A soccer-themed yes/no oracle. Ask a yes-or-no question out loud, then take 5 penalties
from a behind-the-ball point of view. Beat the brutal goalkeeper **3 times out of 5** and
the oracle says **YES** — fall short and it says **NO**.

## Play

Open `index.html` in any browser. No build step.

For local serving:

```bash
node server.js   # serves on http://localhost:4180
```

## Features

- Player POV with a perspective pitch, converging penalty box, and a distant goal
- Animated ball flight (arc + spin) and a reactive, diving goalkeeper
- "Brutal keeper" difficulty: exact + fingertip saves, plus a chance to shoot off target
- Five aim zones (top/bottom left, middle, top/bottom right), sized for mobile taps
- Minimal HUD: five red/green result circles

## Ads

A bottom banner is scaffolded for Google AdSense. Search `ca-pub-XXXXXXXXXXXXXXXX` in
`index.html` and follow the inline instructions to plug in your publisher and slot IDs.
Until configured, a styled placeholder is shown.
