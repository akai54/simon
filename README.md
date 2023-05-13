<h1 align="center">Simon Game in Godot</h1>

<div align="center">
A try to reproduce the famous Simon game using the Godot engine, Visual Script only.
</div>

## Change Log

All notable changes to this project will be documented here.

## [0.4]

### Added

- New Background image
- Sounds for buttons

### Changed

- Labels names became more significant, like (label -> score_value).
- Blue color changed into a more cyan one.
- No more need to show color name after pressing the button.
- Buttons became colored with the corresponding ones instead of just text.
- score_value only contain the value, no more passing other info into the same string.

## [0.3]

### Changed

Changed modes names to the ones planned.

### fixed

- Fix: list_immutable wasn't cleared at each create_array call.
- Fix: score wasn't updated after replaying.

## [0.2]

### Added

New Main Menu scene.

### Changed

Rearranged all scripts in their own folder, the same goes for scenes, assets and themes.

## [0.1]

### Fixed

Reset the sequence length to 4, after losing the set.
