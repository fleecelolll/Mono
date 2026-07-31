## Changelog — 7/31/2026

### Added
- **Fling Player** — pick anyone from the Teleport tab and launch them
- **Chams** — the old through-wall body glow, now its own separate toggle
- **Dropped Gun ESP & Distance** — see the sheriff's dropped gun through walls and view its distance
- **Auto Grab Dropped Gun** — instantly teleports you to the dropped gun, grabs it, and returns you to your original spot

### Changed
- **Box ESP** is now a real 2D box that tracks each player. What used to be called Box ESP was really chams, so it moved to the new **Chams** toggle and **Box Fill** became **Chams Fill**
- **Kill Feed** now works in every role. It only ever fired for the murderer and sheriff before, so innocents never saw a kill feed
- **Teleport To Player** works again — it used to always say it could not find the player no matter who you picked
- **Server Hop** works again — it used to always say there were no open servers
- **Silent Aim** is now **Gun Silent Aim** and only affects the gun
- **Auto Collect Coins** now stops on its own once your coin bag is full
- **Auto Kill** no longer switches itself on, and no longer silently stops working for the rest of the round
- Role detection now works even after you pick up the dropped gun
- ESP no longer draws on top of the menu
- Tooltips are hover based now, so they stop overlapping longer options
- The menu hides itself better — every UI name is randomised each run
- **Throw Knife Through Walls / Shoot Gun Through Walls** works again

### Removed
- **Auto-Combat on Role** — Auto Kill already does exactly the same thing
- **Collect Speed** — anything above the default just gets you kicked
- **No Fog** — MM2 has no real fog to remove
