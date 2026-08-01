## Changelog — 7/31/2026

### Added
- **Fling Player** — pick anyone from the Teleport tab and launch them
- **Chams** — the old through-wall body glow, now its own separate toggle
- **Dropped Gun ESP & Distance** — you can see the sheriff's dropped gun through walls
- **Auto Grab Dropped Gun** — instantly teleports you to the dropped gun and teleports you back to your original spot
- **Instant Knife Throw** — skips the wind up and the flight time, the knife lands the moment you press throw
- **Lookup tab** — full player lookup with their Roblox join date, account age, friends, followers, plus their MM2 level, role, perk and how many Godlys and Ancients they own
- **View Full Inventory** — opens MM2's own profile window for anyone in the server

### Changed
- **Box ESP** is now a real 2D box that tracks each player. What used to be called Box ESP was really chams, so it moved to the new **Chams** toggle and **Box Fill** became **Chams Fill**
- **Kill Feed** now works in every role. It only ever fired for the murderer and sheriff before, so innocents never saw a kill feed
- **Teleport To Player** works again, it used to always say it could not find the player no matter who you picked
- **Server Hop** works again — it used to always say there were no open servers
- **Silent Aim** is now **Gun and Knife Silent Aim** and works with both weapons
- **Trigger Bot** is now **Gun Trigger Bot** and will not fire at people it cannot see
- **Auto Collect Coins** now stops on its own once your coin bag is full, and no longer leaves you stuck inside a wall or the floor when it does
- **Auto Kill** no longer switches itself on, and no longer silently stops working for the rest of the round. It also leads moving targets now instead of only ever hitting people who stand still
- Role detection now works even after you pick up the dropped gun
- **Murderer Notify** is now a notification that stays on screen and counts the distance down as they get closer, instead of a one off popup
- ESP no longer draws on top of the menu
- Tooltips are hover based now, so they stop overlapping longer options
- Search now looks through every tab instead of only the one you are on
- **UI Settings** is far less cluttered — the theme and config sections only keep the parts people actually use
- The menu hides itself better — every UI name is randomised each run
- **Throw Knife Through Walls / Shoot Gun Through Walls** works again, and now needs you to actually aim at someone rather than snapping for you
- Better mobile support — knife throwing and flying both work on touch now
- General optimisation pass, the ESP and coin farm do a lot less work per frame

### Removed
- **Auto-Combat on Role** — Auto Kill already does exactly the same thing
- **Collect Speed** — anything above the default just gets you kicked
- **No Fog** — MM2 has no real fog to remove
