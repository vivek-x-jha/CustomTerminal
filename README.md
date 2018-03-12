# CustomTerminal
Creates custom Bash prompt, colorizes `ls` command, and adds common aliases

![Sample Terminal Session](screenshots/TerminalSession.png "Sample output of a terminal session with custom colors, prompt, and aliases")

## Installation
Open a terminal session and paste the following 4 lines:

```
mkdir -p $HOME/.bash_custom
git clone 'https://github.com/vivek-x-jha/CustomTerminal' $HOME/.bash_custom
echo -e '\nfor file in $HOME/.bash_custom/*.sh; do\n\tchmod +x $file\n\t. $file\ndone' >> $HOME/.bashrc
. $HOME/.bashrc
```
