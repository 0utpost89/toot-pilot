# Toot Pilot

A Flappy Bird-style browser game. A cartoon pilot in pyjamas flies through her house on a gas-powered jetpack, dodging ceiling fans, swinging lamps and teetering stacks of mini backpacks.

Everything is in one `index.html`: the art is drawn with canvas shapes, the sounds are made with the Web Audio API, and there are no external assets or libraries.

## Play

- **Online:** https://0utpost89.github.io/toot-pilot/
- **Install it as an app:** open the online link in Chrome (Android or desktop) and tap **INSTALL APP** on the title screen, or use the browser menu's *Install app* / *Add to Home screen*. On iPhone/iPad, open it in Safari, tap Share, then *Add to Home Screen*. It gets its own icon, runs full-screen and works offline.
- **Offline file:** download `index.html` and open it in any modern browser.

## Controls

- **Tap, click, Space, Up arrow or W:** toot upward
- **Hold:** sustained thrust (a turbo toot)
- **M** or the speaker button: mute everything
- **N** or the music-note button: music on/off

Your high score is saved in your browser.

## Toot Coins & the shop

- Grab **Toot Coins** as you fly: coins are worth 1, banknotes 5, and the rare bundle near a gap's edge is worth 25. They're saved in your browser between games.
- Spend them in the **shop** (button on the title and game-over screens, or press **S**): new pyjamas to wear, and special mini backpacks that start turning up in the floor stacks.
- Look out for the **fizz bottle**: a few seconds of double points, with a slightly tipsy wobble.
- Grab a **chocolate bar** for a shield: the next crash just snaps the chocolate instead of ending your run.

Keep an eye on the windows for the odd plane flying past, and fireworks (especially when you rank up). Every so often she pipes up with one of her sayings in a speech bubble; add more to `SAYINGS` in the script.

## Tweaking

Gravity, thrust, scroll speed, gap sizes, coin, fizz and chocolate chances are in the `CONFIG` object at the top of the script. Shop prices are in `PYJAMAS` and `BAG_DESIGNS`.

## Seasons

The game dresses up for the time of year: **Halloween** (10 Oct – 2 Nov: pumpkins, a ghost-costumed cat, bats, cobwebs, bunting), **Christmas** (1 Dec – 6 Jan: snow, Santa's sleigh, a fireplace with stockings and milk & cookies, a tree, wreaths, fairy lights) **Valentine's** (1 – 15 Feb: roses, cards, candles, chocolates, rose petals, a heart garland) and **Easter** (two weeks before Easter Sunday to Easter Monday, worked out each year: egg baskets, a chocolate bunny, daffodils, hanging painted eggs, egg bunting, eggs hidden on the floor and the Easter bunny hopping past outside).

During a season the shop has a limited-time tab of seasonal pyjamas and bags. Anything you buy goes into your **Walk-in Wardrobe** (button on the title screen, or **W**) and stays there all year, even after it leaves the shop.

To preview a season, add `?season=christmas` (or `halloween`, `valentines`, `easter`, `none`) to the address.

## Music

An original, bouncy mariachi-brass tune (two trumpets in harmony, oompah tuba, offbeat chords, light drums and the odd taxi "beep-beep") is synthesised live from the `SONG` data in the script, so there are no audio files. It speeds up a little as your score climbs; ranking up gets a trumpet fanfare, and crashing gets a sad trombone.
