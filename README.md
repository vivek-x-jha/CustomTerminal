# CustomTerminal
Creates custom Bash prompt, colorizes `ls` command, and adds common aliases

![This is a demonstration of my customized Bash terminal](https://imgur.com/a/M8DMV "Sample terminal session")

## Installation
Open a terminal session and paste the following lines of code:

```
CUSTOM="${HOME}/.bash_custom"
mkdir ${CUSTOM} && cd ${CUSTOM}
```
Now clone the repository to your local:

```
git clone "https://github.com/vivek-x-jha/CustomTerminal"
```

Finally, paste the following commands:

```
echo -e "\nchmod +x ${CUSTOM}/*.sh" >> "${HOME}/.bashrc"
echo -e "\n${CUSTOM}/customize_prompt.sh" >> "${HOME}/.bashrc"
echo -e "\n${CUSTOM}/colorize_ls.sh" >> "${HOME}/.bashrc"
echo -e "\n${CUSTOM}/git_aliases.sh" >> "${HOME}/.bashrc"
```
