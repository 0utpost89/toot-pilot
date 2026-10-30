# Toot Pilot

A Flappy Bird-style browser game. A cartoon pilot in pyjamas flies through her house on a gas-powered jetpack, dodging ceiling fans, swinging lamps and teetering stacks of mini backpacks.

Everything is in one `index.html`: the art is drawn with canvas shapes, the sounds are made with the Web Audio API, and there are no external assets or libraries.

## Play

- **Online:** https://0utpost89.github.io/toot-pilot/
- **Offline:** download `index.html` and open it in any modern browser.

## Controls

- **Tap, click, Space, Up arrow or W:** toot upward
- **Hold:** sustained thrust, which drains the gas tank
- **M** or the speaker button: mute

Collect the cans of baked beans for bonus points and a gas refill. Your high score is saved in your browser.

## Toot Coins & the shop

- Grab **Toot Coins** as you fly: coins are worth 1, banknotes 5, and the rare bundle near a gap's edge is worth 25. They're saved in your browser between games.
- Spend them in the **shop** (button on the title and game-over screens, or press **S**): new pyjamas to wear, and special mini backpacks that start turning up in the floor stacks.
- Look out for the **fizz bottle**: a few seconds of bottomless gas and double points, with a slightly tipsy wobble.
- Grab a **chocolate bar** for a shield: the next crash just snaps the chocolate instead of ending your run.

Keep an eye on the windows for the odd plane flying past, and fireworks (especially when you rank up).

## Tweaking

Gravity, thrust, scroll speed, gap sizes, the tank's drain and refill rates, coin, fizz and chocolate chances are in the `CONFIG` object at the top of the script. Shop prices are in `PYJAMAS` and `BAG_DESIGNS`.
