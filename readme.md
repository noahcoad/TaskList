# Task List
A [Sublime Text](https://www.sublimetext.com/) Plugin

## Description

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

## Also
Check out my other [Sublime Text packages](https://gist.github.com/noahcoad/712ba4e38467f5126eb8cedd9ecbc842)