# zombie
Tool to emulate the .screenrc zombie command for a single window
## Usage:
zombie \[keys\] \[command \[args\]\]
### \[keys\]
keys is two characters. After the command exits you can enter either the first or second character.
Entering the first character will terminate the loop and exit zombie while pressing the second character will restart the command.
### \[command \[args\]\]
Aside from the loop the command should behave just the same as if you were running outside of the script.
## Requirements:
Requires bash installed as /bin/bash
