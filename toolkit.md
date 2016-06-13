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


Move whole lines up or down the page in sublime without copying or pasting anything:
<br>
'ctrl +cmd + up arrow or down arrow'
<br>
Copy whole lines of code:
<br>
'cmd + shft + d'

## Clean up node_modules folders
A few weeks ago I discovered over 6Gb worth of node modules on my computer.  These folders build up, and you forget about them.  You can git rid of them all one command line action.  First navigate to your workspace/ directory, where you keep all your projects.  The command: `$ find . -name "node_modules" -exec rm -rf "{}" \;` will recursively search and delete files and fodlers called 'node_modules'.  

## Save on focus loss
I had been using the sublimetext 3 package 'autosave', but saving on every tiny change had been interfering with the handy dropdown thing in sublime. This is way cooler and less annoying:

Save "save_on_focus_lost": true to preferences -> setting-user




