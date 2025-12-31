# Changelog - XToLevel

All notable changes to this project will be documented in this file.

## [3.3.5_15r-PA] - 2025-12-30

### Fixed
- **Pet.lua:** Fixed "table index is nil" error in `AddKill` function.
- Added a guard to ensure `self.name` (pet name) is valid before being used as a table key.
- Improved reliability when summoning or initializing pets while gaining XP.

## [3.3.5_14r] - Legacy
- Added a "Time to level" feature.
- The tooltip for mobs now shows how many of those mobs you need to kill to reach your next level.
- The Mob XP algorithm has been tweaked to take heirloom items into account.
- Added the option to display rested and raw XP values in custom LDB patterns.
- Added options to have the LDB XP values count down rather than up.
- Added a new LDB pattern, "countdown".
- Fixed a bug that caused the LDB label to display even when disabled.
