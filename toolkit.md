## Useful terminal commands

create a new file `touch <newfile.js>`
create a new folder `mkdir <newfolder>`
ReMove `rm`
MoVe   `mv`
CoPy   `cp`
LiSt   `ls`


You can add a custom sublime shortcut that inserts the text `console.log()`.  I made this because it is the command I use most often.  Open Sublime, click Sublime Text from the menu, preferences, key bindings - user.
My file looks like this:
`[{"keys": ["alt+z"], "command": "insert_snippet", "args": {"contents": "console.log()"}},]`
This means I can press alt-z in sublime, and `console.log()` appears before my cursor.

## My top 5 Git tools:
- Git guis (GITX is my fave)
- `git reset --soft HEAD~1` (undoes your last commit and keeps the changes in your staged area)
- git rebase branch (useful instead of git merge, give it a play)
- git stash && git stash pop
- git cherry pick COMMIT_ID (cherry picks a specific commit onto your branch. super useful)