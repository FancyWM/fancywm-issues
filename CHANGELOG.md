# Changelog

## v2.4.1
- Fix crashes for some apps with custom-drawn frame

## v2.4.0
- Scripting support (preview) #20
- Added dedicated keybindings per virtual desktop
- Fixed lost window size when restored #27
- Fixed "Open in Text Editor"
- Fixed incorrect font scaling on multiple monitors
- Fixed broken process ignore list
- Fixed text cutoff in settings #22

## v2.3.5
- Multiple monitor fixes

## v2.3.4
- Bug fixes

## v2.3.3
- More Mica material
- Bug fixes

## v2.3.2
- Bug fixes

## v2.3.0
- Added window resizing keybindings!
- Mica is now used in the overlay and settings (faux Mica)
- FancyWM will now try to automatically stack new windows instead of giving up and enabling floating mode
- FancyWM will now try to pull up windows beyond their parent panel when the window cannot fit in the parent
- The focused window highlight now disappears more quickly
- Improved responsiveness when resizing windows
- Miscellaneous bug fixes

## v2.2.0
- Window padding not duplicated (#13)
- Highlight the focused window during command pop-up (on by default) (#15)
- Disable rounded corners on Windows 10
- Improved tie-breaking when no permissible arrangement can be computed

## v2.1.0
- Added new "Move window" keybindings
- Window items in the panel overlays can be scrolled with the mouse wheel
- The Cancel action (default: [Esc]) is now reassignable in the Settings
- "Move focus left" now focuses the first window in the panel, instead of the last (more intuitive)