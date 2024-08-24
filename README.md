# sobriquet


## PROJECT DESCRIPTION

The project is a collection of linux terminal aliases. Aliases are basically abbrviations of commands used in the linux terminal. They reduce the amount of writing and make work much faster. Alias can be placed in the .bashrc file in the home directory.

The basic syntax for an alias is:
alias SHORT_COMMAND='ORIGINAL_COMMAND'

- Example: alias ls='ls -lah'

## HOW TO INSTALL ON BASH

1. git clone https://github.com/betnero/sobriquet
2. Copy the contents of the aliases.txt file.
3. sudo nano .bashrc
4. Paste the copied text below the contents of the .bashrc file.
5. To apply changes enter:
source ~/.bashrc 
OR
. ~/.bashrc

## HOW TO INSTALL ON ZSH (KALI LINUX)

1. Kali Linux on release 2020.4 and later uses zsh as the default shell. Steps to apply the aliases in such case are listed below.
2. git clone https://github.com/betnero/sobriquet
3. cd ~
4. sudo nano .zsh_aliases
5. Enter the aliases of your choice (e.g. alaia bye='sudo shutdown now') and save the changes
6. sudo nano .zshrc
7. Enter the following code at the end of the file:

if [ -f ~/.zsh_aliases ]; then
 . ~/.zsh_aliases 
fi

9. Save the changes and close the file.
10. To apply changes enter:
source ~/.zshrc
OR
    /.zshrc

## HOW TO CONTRIBUTE

Check: CONTRIBUTING.md
