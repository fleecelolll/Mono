# MONO MM2 — Changelog

**Release date:** August 10, 2026

## Added

- **Touch Controls** — On-screen buttons for **Fly Up**, **Fly Down**, and **Aimbot**, so those features are usable on mobile. Enables itself automatically on touch devices.
  - The pad is draggable, and each button only appears while its feature is turned on.

- **Silent Aim Ignores FOV** — Targets the nearest enemy regardless of where your camera or cursor is pointing, instead of only targeting someone inside the Aim FOV circle.

## Changed

- On touch devices, the custom cursor is now disabled and the interface scales up for larger tap targets.

## Removed

- **Sheriff and Hero Auto Kill** — The gun could not reliably hit a moving target, so the gun branch was removed rather than shipped as something that only worked against a stationary player. **Auto Kill is now Murderer only.**

- **Gun Silent Aim** — Removed for the same reason. The toggle is now **Knife Silent Aim**.

- **Gun Trigger Bot** — Removed for the same reason.

## Fixed

- Fixed walking strangely until you jumped after **Auto Collect Coins** or **Noclip** turned off.

- Fixed the **Kill Feed** showing Sheriff deaths late.

- Fixed unloading leaving features and menus behind instead of fully cleaning up.

- Fixed **Anti Fling** only catching the most extreme flings.

- Fixed the menu being stuck at nearly fullscreen on phones.

## Optimized

- **Box ESP** and **Skeleton ESP** now run as a single pass instead of two separate ones.

- Significantly less repeated work every frame, so the script runs smoother — especially on mobile and in full servers.

## Known Issues

- Fling is not working properly.

- Anti Fling still fails in some cases.

- Getting teleported back to the map and then to the lobby very quickly once a round ends.
