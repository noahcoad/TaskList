# Task List
A [Sublime Text](https://www.sublimetext.com/) Plugin

Toggles an Task List emoji in front of a line. \
Similar to "Toggle Comment", but cycles through emoji "icons".

Command is called "Toggle Task List". \
I recommend mapping to <kbd>option+command+t</kbd> on mac. \
To do that, 'Sublime Text' menu > 'Settings...' menu > 'Key Bindings' menu > and add `{ "keys": ["super+alt+t"], "command": "toggle_task_list" }` to the right (user) side.

Defaults: \
✡️ to do \
✅ done \
✴️ highlight / warning \ 
🅿️ informational / in progress \
🆘 not done / error \

Edit `task_list.sublime-settings` to alter the emoji icons list to be used.

## For Example: `todo.txt`

```
:: today
✅ order parts for automated sprayer
✡️ update architecture diagram
✡️ create POC proposal 

:: archiv
✅ change flight to Japan
✡️ mail package to brother
```

## See Also
Check out my other Sublime Text plugins:
* [Open URL](https://github.com/noahcoad/open-url) .. hit a hotkey to open the url/file/folder under the cursor
* [Google Spell Check](https://github.com/noahcoad/google-spell-check) .. uses Google to check words and phrases
* [Auto Open Notes](https://github.com/noahcoad/sublime_auto_open_notes) .. automatically opens a notes.txt or readme.md file when opening a folder in a new window
