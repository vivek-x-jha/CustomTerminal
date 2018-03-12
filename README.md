# CustomTerminal
Creates custom Bash prompt, colorizes `ls` command, and adds common aliases

![Sample Terminal Session](screenshots/TerminalSession.png "Sample output of a terminal session with custom colors, prompt, and aliases")

## Installation
Open a terminal session and paste the following line:

```
mkdir -p $HOME/.bash_custom
```

Now clone the repository to your local:

```
git clone 'https://github.com/vivek-x-jha/CustomTerminal' $HOME/.bash_custom
```

Paste the following command to add to your `.bashrc`:

```
echo -e '\nfor file in $HOME/.bash_custom/*.sh; do\n\tchmod +x $file\n\t. $file\ndone' >> $HOME/.bashrc
```
Finally, reload your shell:

```
. $HOME/.bashrc
```
