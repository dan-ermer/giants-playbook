# Giants Flag Football Play Book

The 2026 Giants NFL Flag football playbook, redrawn as an easy-to-read web page.

## What's in it

All 11 plays from the coach's sheets, with the same numbers, names, and formations:

| # | Play | Formation | Type |
|---|------|-----------|------|
| 1 | HB Dive | Slot Right | Run |
| 1 | HB Dive | Trips Right | Run |
| 2 | Fake HB Dive Slot Reverse | Slot Right | Run |
| 3 | Pass | Slot Right | Pass |
| 4 | Run Pass Option Half Back Toss | Slot Right | Run or Pass |
| 5 | Fake HB Dive, Fake Slot Reverse, End Around Handoff | Slot Right | Reverse Run |
| 6 | Hitches | Slot Right – Empty | Pass |
| 7 | Delay Pass | Slot Right | Pass |
| 8 | Split End Pass | Trips Right | Pass |
| 9 | Bootleg Pass Right | Slot Left | Pass |
| 10 | End Motion Reverse Handoff | Overload Right | Run |

## How to use it

- Pick a play from the list, or use the **Prev** / **Next** buttons (or the left and right arrow keys).
- Each player has one color on every play: **L** yellow, **S** orange, **R** pink, **H** blue, **Q** white, **C** gray square.
- The player who gets the ball has a dashed ring and a **Gets the ball** tag.
- Tap a player's card to show only that player's route. Tap again to show everyone.
- Press **Run it ▶** to watch the players move along their routes.
- Link straight to a play by adding `#p` and its position in the list to the URL, for example `#p5`.

### Reading the diagram

- **Solid line with an arrow:** run this way.
- **X:** stop here, turn, and look for the ball.
- **Dotted line:** the ball is handed or tossed.
- **Blue line:** line of scrimmage.

## Notes

The written "who does what" instructions are based on the coach's hand-drawn sheets. A few things are worth checking with the coach:

- Play 5: no route is drawn for R.
- Play 8: assumes R throws the pass after catching the backward toss from Q.
- Play 9: no route is drawn for C.

## Hosting

The whole site is a single `index.html` file with no build step. It's served with GitHub Pages from the `main` branch (Settings → Pages → Branch: `main`, folder `/ (root)`).

To update a play, edit the `PLAYS` list near the bottom of `index.html` and commit the change.
