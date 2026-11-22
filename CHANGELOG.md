# Changelog

## 1.0.6

- Changed: the soft cue sound no longer uses the whisper sound; now a map ping.
- Added: sound dropdowns in the options panel to pick the alert and soft sounds (selecting one previews it).

## 1.0.5

- Added: soft one-shot sound for the expiring, no auto attack, too far and facing warnings (`/seal sound2`, or the options panel).
- Added: short debounce on the NO AUTO ATTACK warning so it doesn't flash when swings toggle on.
- Added: `/seal discord` and `/seal donate`, plus copyable feedback and donation links in the options panel.
- Added: addon version shown in the options panel and `/seal status`.

## 1.0.4

- Changed: addon renamed to Espi Paladin Utils (display name only; settings and `/seal` commands are unchanged).

## 1.0.3

- Added: orange "TOO FAR" / "FACE TARGET" warning when auto attack is on but your swings can't land (out of melee range or facing the wrong way). Shares the `/seal attack` toggle.

## 1.0.2

- Added: orange "NO AUTO ATTACK" warning when you're in combat with an attackable, engaged target but aren't auto-attacking. Silent; toggle with `/seal attack` or the options panel.

## 1.0.1

- Removed: Judgement no longer clears the tracked seal (on Forever it doesn't consume your seal), fixing a false NO SEAL after judging.

## 1.0.0

Initial release.

- In-combat "NO SEAL" warning for Paladins, with an optional sound alert.
- Icon shows your last-used Seal and remembers it between sessions.
- Casting Judgement clears the tracked seal, so NO SEAL fires right after you judge.
- "SEAL EXPIRING" cue with a countdown when a seal is about to drop (default 5s, configurable, 0 = off).
- Optional repeating warning sound while unsealed.
- Combat-start grace period (default 1s) so the alert doesn't flash while you cast your opening seal.
- Reloading mid-fight doesn't trigger a false NO SEAL; warnings pause until that fight ends.
- Optional hiding while mounted or in a vehicle.
- Draggable icon; warning text scales with icon size. Unlocked mode shows a green "DRAG ME" frame so it can't be mistaken for an alert.
- Options panel (`/seal config`) and slash commands (`warn`, `repeat`, `grace`, `mounted`, `vehicle`, `config`, and more). Every change is confirmed in chat.
