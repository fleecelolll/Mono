# MONO MM2 — Changelog

**Release date:** August 8, 2026

## Added

- **Fling All Players** — Flings everyone in the server one after another, then returns you to your original position.

- **Auto Fling Murderer** — Automatically and repeatedly flings the Murderer whenever they are detected.

- **Auto Fling Sheriff** — Automatically and repeatedly flings the Sheriff or Hero whenever they are detected.

- **Trap ESP** — Shows invisible Murderer traps through walls.  
  **Note:** This feature is currently marked as untested.

- **Anti Trap** — Restores your movement after a Murderer trap slows you.  
  **Note:** This feature is currently marked as untested.

- **Anti Fling** — Limits extreme velocity and spin, removes unwanted body movers, and prevents other characters from colliding with you.

- **Server Tab** — Displays live server information, including:
  - Player count
  - Region code
  - Server type
  - Server uptime
  - Your ping
  - Server FPS
  - Place version
  - Job ID

- **Copy Job ID** — Copies the current server's Job ID to your clipboard.

## Changed

- **Fling Player** was completely rebuilt to:
  - Follow moving targets more reliably
  - Force the collision state needed for the fling
  - Restore your character's physics afterward
  - Hold your return position instead of launching or leaving you stuck

- **Aim Prediction** now uses smoothed, ping-aware movement tracking with capped lead and jump prediction instead of relying on a single raw velocity sample.

- **Murderer Aimbot** now considers every other living player instead of targeting only the Sheriff or Hero.

- **Auto Kill** and **Gun Trigger Bot** now check for targets and fire more frequently.

- **Sheriff and Hero Auto Kill** now respects the **Gun Through Walls** setting instead of always bypassing walls.

- **Sheriff and Hero Auto Kill** now warns that gun hits against moving targets may still be unreliable.

- **Instant Knife Throw** now automatically equips a stowed knife and uses a shorter cooldown based on `ThrowSpeed`.

- **Dropped Gun ESP** and **Auto Grab Gun** now:
  - React immediately when the dropped gun appears
  - Refresh more quickly
  - Avoid attempting to grab the gun while you are dead
  - Avoid interfering with round-transition teleports

- **Auto Collect Coins** now idles when:
  - You are dead
  - You are between rounds
  - No nearby coins are available
  - Your coin bag is full

  It also restores your movement cleanly when it stops farming.

- **Box ESP** and **Skeleton ESP** now work on executors without the `Drawing` API.

- **Skeleton ESP** now skips off-screen players to reduce unnecessary work.

- **ESP**, **Coin ESP**, and **Kill Feed** now refresh more quickly while improved tag and UI caching reduces repeated work.

- **Silent Aim** now has a gun fallback for executors that cannot install the normal namecall hook.

- The menu can now fall back to `PlayerGui` when executor GUI or `CoreGui` access is unavailable.

- The main window now sizes itself according to the current viewport.

- Notifications now stack upward from the bottom-right corner.

- **Minimize To Square** is now enabled by default.

- The default unsaved theme is now MONO's dark monochrome color scheme.

- Combat controls are now organized into:
  - Murderer features
  - Shared aim features
  - Sheriff features

- **Rejoin** and **Server Hop** were moved from the Safety tab to the new Server tab.
## Removed

No user-facing features were removed in this update
