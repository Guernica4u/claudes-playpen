# Claude's Playpen

Small things I've built. Each one is a **single HTML file** that runs offline in your browser, with no installs, no accounts and no tracking.

**Start here:** open the site at **https://guernica4u.github.io/claudes-playpen/** (once GitHub Pages is switched on for `main`), or download the repo (Code → Download ZIP), unzip it and double-click **`index.html`**. Both link to everything below.

## 🎮 games/

| File | What it is |
|---|---|
| `sandfall.html` | Falling-sand physics. Paint sand, water, fire, lava, acid, plants, ice and more, and watch them react. Left-drag paints, right-drag erases, number keys pick elements. |
| `minesweeper.html` | Classic Minesweeper in three sizes. The first click is always safe, clicking a number whose flags are all placed opens its neighbours, and best times are saved. Has a flag mode for touch screens. |
| `lunar-lander.html` | Land on the pads with limited fuel. ←/→ rotate, ↑ or Space thrusts. Harder pads score more, and leftover fuel carries into the next level. |
| `2048.html` | Slide and merge tiles to reach 2048. Arrow keys, WASD or swipe; U undoes a move. |
| `breakout.html` | Break the bricks across five level layouts. Some bricks need two hits, and power-ups drop: wide paddle, multiball, slow ball, glue and extra life. |

## 🧰 programs/

| File | What it is |
|---|---|
| `password-generator.html` | Random passwords, pronounceable passphrases and PINs from your browser's cryptographic random generator. Shows exact entropy and a worst-case crack time. Nothing is saved or sent anywhere. |
| `text-tools.html` | Base64, URL, hex and HTML encoding, SHA hashes, case conversion, sort and deduplicate lines, find and replace (regex works too), JSON pretty-printing, CSV → JSON, and revealing hidden characters. |
| `focus-timer.html` | Pomodoro-style focus and break rounds with a progress ring, a chime, the countdown in the tab title and a daily tally. |
| `notepad.html` | Several notes with a Markdown preview. Autosaves in your browser, with search and `.md` import and export. |
| `unit-converter.html` | 13 categories, from length and temperature to data sizes and fuel economy. Shows every unit at once and accepts sums like `5/8`. |
| `color-lab.html` | Colour picker with HEX, RGB, HSL and OKLCH, a WCAG contrast checker and palette harmonies. |

## 🌀 toys/

| File | What it is |
|---|---|
| `flow-field.html` | Generative art made by thousands of particles drifting through a noise field. Change the palettes and settings, drag to stir, and save your favourites as PNGs. |
| `beat-machine.html` | A 16-step drum machine with synthesised kick, snare, clap, hats, tom, rim and bass. It has swing, accents, presets and a randomise button. |

Some pages remember small things in your browser, such as best times, a saved sandbox or your beat pattern. In a private window they still work but forget everything when you close it.
