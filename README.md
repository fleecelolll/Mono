# MONO MM2 - Changelog

**Release date:** August 27, 2026

## Added

- **New menu** - Mono has its own custom and unique menu now instead of one borrowed from somewhere else. The menu no longer downloads itself when you run the script, so it opens faster and cannot fail to load.
  - Six tabs: **Modules**, **Players**, **Server**, **Configs**, **Settings** and **Credits**.

- **Per-feature settings** - Each feature's options are now grouped with it behind the three dots on its row, along with a full explanation of what it does, instead of being spread across the page.

- **Favorites** - Star a feature and it goes to the top of the list.

- **Keybinds on everything** - Click the key chip on any row and press a key, right click to clear it. Before this only **Aimbot** and the menu itself could be bound.

- **Guided tour** - A short walkthrough of the menu the first time you run the script. You can replay it any time from **Settings**.

- **Fullscreen** - Expand the menu to fill the screen.

- **Compact mode** - Smaller rows for more on screen at once. Sweep your mouse to the left edge to bring the category list back.

- **Menu customization** - Accent color, font, text size, opacity, menu size, where the categories sit and where the search bar sits, plus a button to reset it all.

- **Sheriff and Hero Auto Kill** - Back after being removed last update for not hitting moving targets. It works now.

- **Gun Silent Aim** - Also back. **Silent Aim** now covers the gun as well as the knife.

- **3D Box ESP** - A box drawn around the player in the world, so it turns with them.

- **Tracers** - A line pointing to each player. You choose where it starts from.

- **Footstep Trails** - Colored footprints behind every player. Red for the murderer, blue for the sheriff, green for innocents. Only you can see them.

- **Avatar Icons** - Each player's headshot on their nametag.

- **ESP Distance Limit** - Hide nametags and tracers past a distance you pick.

- **Loop Fling** - Keeps flinging one player over and over. It waits for them to land first, so it will not follow them into the void.

- **FPS Cap** - Limit your frame rate so your phone or laptop does not get hot. Turning it off puts you back on the limit you had before.

- **Players tab** - Everyone in the server. Click a player to see their level, prestige, XP, perk and equipped knife and gun, each with a copy button.
  - Mark someone as your target and the teleport and fling features will use them.

- **Auto Save Toggles** - Off by default. Turn it on and your toggles save as you change them and come back next time.

- **Compatibility check** - Tells you if your executor is missing something Mono needs, and which features are running in a weaker mode because of it.

## Changed

- **Server tab** - Expanded from eight rows to place and creator details, IDs, memory, gravity, clock time and graphics quality, with a copy button on every row instead of just one for the Job ID.

- **Configs** now have their own tab, with each saved config listed and its own load, overwrite and delete buttons.

- **Player Lookup** is now the **Players** tab.

- **Chams Fill** is now a setting inside **Chams** instead of its own toggle.

- Touch controls for **Fly** and **Aimbot** appear on their own on phones. There is no toggle for them any more.

- The minimized menu is now a badge you can drag anywhere instead of being stuck to the side of the screen.

- Configs are now saved in a folder called **Mono MM2**.

## Removed

- **Parts of Player Lookup** - The **Players** tab shows account details and MM2 level, prestige, XP, role, perk and equipped knife and gun. What is gone is the join date, friends and followers counts, the weapon rarity counts (Godly, Ancient, Legendary, Unique), pets, effects and trade counts, and the full inventory viewer. This may come back later.

- **Theme picker** - Replaced by the accent color, font, text size and opacity settings.

- **Autoload Selected** - Replaced by **Auto Save Toggles**, which saves and restores your setup on its own.

## Fixed

- Fixed **Fling** not working. This was the main known issue last update.

- Fixed **Anti Fling** failing. This was also a known issue last update.

- Fixed **Anti AFK** throwing your knife. It used to right click to keep you awake, so if you walked away holding a weapon it would throw it for you.

- Fixed **Box ESP** not fitting the player. The old box was always the same shape no matter what the player was doing.

- Fixed **Fullbright** making the map darker instead of brighter in some places.

- Fixed **Fling All Players** skipping players who are dead but still have a body.

- Fixed **Teleport To Player** saying it worked when you have no character.

- Fixed ESP keeping a dead player's old role color instead of showing them as innocent.

## Optimized

- The menu is no longer downloaded when the script starts, so it loads faster.

- **Skeleton ESP** is much lighter. It was doing nearly twice the work it needed to.

- Players behind you are skipped instead of being worked out and then hidden.

- Coin scanning only runs while **Coin ESP** or **Auto Collect Coins** is on. It used to run five times a second no matter what.

- **Anti Fling** does less work while still checking the same things.

- The menu is quicker to open, which you will notice most on phones and weaker devices.

## Known Issues

- **Trap ESP** and **Anti Trap** are still unconfirmed. Murderer traps show up rarely enough that neither has been seen working in a real round yet.
