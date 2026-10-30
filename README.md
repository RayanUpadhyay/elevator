# elevator.rayanupadhyay.com

An elevator that only goes up. Every floor is somewhere else.

**Live:** [elevator.rayanupadhyay.com](https://elevator.rayanupadhyay.com)

## Features

- A first-person 3D elevator with a brass button panel, a floor display, sliding doors and an arrival ding
- Twelve floors you can step out onto and explore:
  - L: a hotel lobby
  - 2: an empty office in the rain
  - 3: a forest growing through the carpet
  - 4: a birthday party nobody came to
  - 5: the open ocean
  - 6: another elevator, facing you
  - 7: an endless library
  - 8: a desert with one vending machine
  - 9: an alternate-universe version of my room
  - 11: above the clouds
  - 12½: a crawlspace
  - ∞: the roof
- There is no 10 and no 13
- It starts cosy and gets slowly stranger the higher you go: the elevator music drifts out of tune and the lights get less reliable
- A door-close button that does nothing, and an alarm bell
- Elevator music and the sound of every floor, generated live in the browser
- Remembers which floors you've visited on your device
- Works on phones: left thumb to walk, drag to look, tap the panel. On a computer: WASD and drag to look

## Tech

A single `index.html` with three.js r128 from cdnjs and the Web Audio API, no build step and no image or sound files: every texture and sound is made in code. Each floor is built when you arrive and cleared when you leave. Hosted on Vercel.
