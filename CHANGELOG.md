# TodoReview Changelog

## 6.0.1

- fix: make mypy happy
- fix: modules should be reloaded when update plugin
- refactor: simplify `boot.py`

## 6.0.0

- refactor: drop ST 3

## 5.1.1

- fix: replace set_syntax_file() with assign_syntax()

## 5.1.0

- feat: improved color highlighting
- chore: update todo patterns

## 5.0.0

- feat: popup dialog if file not saved
- fix: `fn_to_regex()` doesn't match all dir separators
- feat: drop ST 3 and use Python 3.8

## 4.0.0

- forked by Jack Cherng <jfcherng@gmail.com> (@jfcherng)
- pref: increase performance on large projects
- feat: drop ST 2 (Python 2)
- chore: remove .no-sublime-package

## 3.0.13

- Add: "auto" option for `render_folder_depth` (#166, thanks @dbeckwith)

## 3.0.12

- Upd: Default priority is now 50 (#158, thanks @locomo)

## 3.0.11

- AddL resolve_symlinks option (#107, #155, thanks @drevicko)

## 3.0.10

- Add current_file argument (#146, thanks @marcus-at-localhorst)

## 3.0.9

- Add: Ability to follow symlinks (Thanks @malexer)

## 3.0.8

- Fix: Datestr not being defined

## 3.0.7

- Doc: Fixed a typo (Thanks @nunoh)
- Fix: Removed a double import of sublime (Thanks @mmattes)
- Add: Allow empty notes (Thanks @Eyenseo)
- Fix: Prevent ST3 Glitch Crash (#131, #133) (Thanks @nsfmc)
- Refactor: Cached encoding setting for a speed improvement

## 3.0.6

- Add: Open Files Only Command Pallet Option (#96) (Thanks @zephster)
- Doc: Fixed typo (#94) (Thanks @davidnunez)

## 3.0.5

- Doc: `encoding` setting
- Add: UTF-8 File Fix (#79, #81, #82, #83)

## 3.0.4

- Doc: Folder Depth Support
- Add: Folder Depth Support (Thanks @Rylon)

## 3.0.3

- Doc: Updated ST3 references
- Add: Sublime Text 2 Support

## 3.0.2

- Doc: Settings as an argument
- Add: Sync project settings between refreshes (#71)
- Fix: `include_paths` error (#73) (Thanks @violon3d)

## 3.0.1

- Fix: Rebuild for Package Control

## 3.0.0

- Add: Syntax highlighting for report header
- Add: Search Timer
- Add: Use buffer if already open
- Fix: Opening comment to line (#66)
- Fix: Non UTF-8 Files (#64)
- Doc: New features
- Doc: Outlined arguments (#63)
- Add: `patterns_weight` option (#58)
- Add: `render_maxspaces` option (#59)
- Del: `render_spaces` in favor of maxspaces (#59)
- Add: `render_header_date` option
- Add: `render_header_format` option
- Upd: Report Header
- Add: Refresh function (#60)
- Upd: Changed direction arguments
- Del: Clear keybinding
- Del: Mousemaps
- Upd: Refactored
- Upd: Combined keymaps

## 2.1.6

- Fix: Documentation on clicking
- Fix: Double click in incorrect context (#49)

## 2.1.5

- Upd: Changed proj settings to user settings (#45)
- Upd: Better default settings (#48)
- Upd: Documentation for page up/down
- Del: Shift up/down skipping, selection issues
- Upd: Refactored navigation
- Add: Mouse navigation (#47)
- Add: Navigation Skipping. Thanks @phoopee3 (#46)

## 2.1.4

- Fix: Error due to project settings (#41)

## 2.1.3

- Add: Documentation for regex101 (#40)
- Add: Documentation for `include_paths` and project settings
- Add: Project settings support (#25, #33)
- Add: `include_paths` setting (#34)
- Del: Project import, use project settings (#37, #38, #39)
- Del: Project import readme
- Upd: Fixed formatting

## 2.1.2

- Add: Ability to import project exclusions for files and folders (#33, #25)
- Add: Setting to control project importing
- Add: Documentation on project setting importing
- Upd: Added clarification on other actions readme
- Upd: Fixed readme markdown headers

## 2.1.1

- Upd: Default settings to reflect new glob type of `exclude_folders`
- Add: Documentation surrounding `open_files_only` and `exclude_folders`
- Add: Ability to glob `exclude_folders`
- Add: `open_files_only` setting. Thanks @Nemesarial (#32)
- Add: Ability to use shortcut directories (#31)
- Del: Random comments left over from 2.0.0 migration
- Fix: Navigation no longer scrolls the display horizontally (#28)
- Fix: Removed Async for display, should fix (#22)
- Upd: Refactored Spaces for index fix (#30)
- Upd: Readme
- Upd: Changelog Formatting

## 2.1.0

- Add: Sort by Priority
- Add: Ability to search open files (#19)
- Add: Setting `render_spaces` (#16)
- Add: Setting `render_include_folder` (#12)
- Del: Priority highlighting for priority and critical tags
- Fix: Sidebar option not working on single file (#15)
- Upd: Readme
- Upd: Cleaned some code and converted to tabs

## 2.0.2

- Add: Sublime Menu for Preferences (#13)
- Add: Sidebar Support (#3)
- Fix: Failure to load language file (#10)

## 2.0.1

- Add: Messages for SublimeTODO Migration
- Fix: Syntax Load Problem

## 0.1.0

- Add: Color Scheme Support
- Add: Priority Support
- Add: Tag Support
- Add: Changelog
- Add: Readme
- Del: Old files
- Fix: Setting Issues
- Fix: Result Navigation Issues
- Upd: Code Cleanup
- Upd: Modified the way search paths are inputted
