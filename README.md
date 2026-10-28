# Toot Pilot

A Flappy Bird-style browser game. A cartoon pilot in pyjamas flies through her house on a gas-powered jetpack, dodging ceiling fans, swinging lamps and piles of laundry.

Everything is in one `index.html`: the art is drawn with canvas shapes, the sounds are made with the Web Audio API, and there are no external assets or libraries.

## Play

- **Online:** https://0utpost89.github.io/toot-pilot/
- **Offline:** download `index.html` and open it in any modern browser.

## Controls

- **Tap, click, Space, Up arrow or W:** toot upward
- **Hold:** sustained thrust, which drains the gas tank
- **M** or the speaker button: mute

Collect the cans of baked beans for bonus points and a gas refill. Your high score is saved in your browser.

## Tweaking

Gravity, thrust, scroll speed, gap sizes and the tank's drain and refill rates are in the `CONFIG` object at the top of the script.
