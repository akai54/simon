<h1 align="center">Simon Game in Godot</h1>

<div align="center">
A try to reproduce the famous Simon game using the Godot engine, Visual Script only.
</div>

## Change Log

All notable changes to this project will be documented here.

## [0.5]

### Added

- New buttons colors and border.
- Red background image when user chooses the wrong color.
- New end_game function instead of repeating same blocks for each button.
- Toggle_buttons new function to disable buttons.

### Changed

- Changed buttons pressed functions names into more meaningful ones
  (\_on_button1_pressed => \_on_jaune_pressed)
- Removed the texture rectangle and now the sequence plays directly on the buttons.
- refactored the whole main script and now it's more organised and easy to walk through.
- Changed the shown sentence after losing the sequence.

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
