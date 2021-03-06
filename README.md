# Drawable Notepad
[![Codemagic build status](https://api.codemagic.io/apps/5e9ea4ef23fafc18149bd52a/5e9ea4ef23fafc18149bd529/status_badge.svg)](https://codemagic.io/apps/5e9ea4ef23fafc18149bd52a/5e9ea4ef23fafc18149bd529/latest_build)


Flutter reimplementation of existing [Drawable Notepad App](https://github.com/tmarzeion/drawable-notepad)

Features:
- Rich-text editor
- Drawing on notes
- Saving/Updating/Removing notes
- Saving notes on-fly
- Draw mode setting bar state persistance
- Saved setting of draw/text modes
- Long press on note item -> Modal preview
- Share feature
- Supported languages: English, Polish, German, Russian, French, Japanese, Spanish

TODO:
- Drawing history optimization (don't redraw whole history with every ui update)
- Search feature
- Tests + CI
- Architecture refactor (DI, State management, clean arch)

BUGS:
- First try of modal animation have bad performance.
- Remove scroll on note, make max lines for text edit