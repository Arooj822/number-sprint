# Number Sprint — BrainJoy Games

**Play free in your browser: https://arooj822.github.io/number-sprint/**

Number Sprint is a free solo number-chase game by **BrainJoy Games**. It runs in
any modern browser on phone, tablet, or computer. No sign-up, no downloads,
no purchases.

## How to play

- Tap **Start level**. After a 3-2-1 countdown, your grid fills with the
  numbers 1 to 25 in a random order, and 3 tiles turn golden.
- A number is called at the top. Find it on your grid and tap it before the
  fuse empties.
- Clear every call in the level to unlock the next one. You can miss at most
  2 calls; a 3rd miss fails the level and you retry it.
- Each level adds more calls and a shorter fuse: level 1 starts with 10 calls
  and a 10-second fuse, and later levels run up to 25 calls with the fuse
  tightening to 4 seconds.

## Scoring

- Correct tap: (100 points plus 10 per second left) x your multiplier.
- Multiplier grows by one every 4 correct taps in a row, up to x5.
- Every 7th call is a turbo call: a short fuse and double points.
- Golden tile: +150 points and +1 star when you tap it as the called number.
- Line complete: +250 points and +1 star (5 rows, 5 columns, 2 diagonals).
- Clean sweep, all 25 numbers tapped with no misses: a big bonus.

Cleared levels and your best score save on your device.

## Tech

A single self-contained `index.html` (HTML/CSS/vanilla JavaScript), hosted on
GitHub Pages. No build step, no dependencies, no tracking.
