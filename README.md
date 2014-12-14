description
=
[cmd.exe](http://en.wikipedia.org/wiki/Cmd.exe)'s prompt displaying:
* date
* time
* hostname
* username
* sharename
* current directory
* the directory stack's depth

respectively, in a colorful format, in a line, and then adding a new line with the greater-than (`>`) character for indicating user input

instructions
=
install `ansicon.exe` to enable ansi colors on console by issuing `autorun.exe -i` command, and then run `coolprompt.bat` script file to set the prompt string for `cmd.exe` as described above. to change the prompt back for the session issue `prompt` command, to change it back permanently (for the process) issue `setx prompt $p$g`
