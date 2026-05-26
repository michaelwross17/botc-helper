# Blood on the Clocktower — Home Game Helper

A web app to speed up running BotC at home — especially the first night setup.

## Status

**Stage 1: Storyteller setup** (this version). Build/import/edit scripts, set
player count, see the bag composition.

**Stage 2** (next): Players join from their phones via a room code, app deals
roles privately to each player and delivers first-night info, storyteller gets
a digital grimoire for the whole game.

## How to run it

1. Open `index.html` in any modern browser (Chrome, Firefox, Edge, Safari)
   by double-clicking it, or right-click → Open with.
2. Click **I'm the Storyteller**.
3. Pick a script (Trouble Brewing / Bad Moon Rising / Sects & Violets),
   import a custom JSON, or start blank. Set your player count.

Your work auto-saves to your browser. If you change browsers or computers,
use **Export JSON** to take your custom script with you.

## What's in this folder

- `index.html` — landing page (Storyteller / Player choice)
- `storyteller.html` — the storyteller workflow (script editor + bag setup)
- `data/` — character + edition + jinx + night-order data
  (sourced from the open-source [Pocket Grimoire](https://github.com/Skateside/pocket-grimoire) project)
- `README.md` — you're reading it

## Importing scripts

The **Import JSON** button accepts the standard format produced by the
official Blood on the Clocktower script tool — an array starting with a
`_meta` object, followed by character IDs as strings. Custom (homebrew)
characters defined inline are recognized but not yet supported for
automated logic in Stage 1.
