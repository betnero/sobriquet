# sobriquet


## PROJECT DESCRIPTION

The project is a collection of linux terminal aliases. Aliases are basically abbrviations of commands used in the linux terminal. They reduce the amount of writing and make work much faster. Alias can be placed in the .bashrc file in the home directory.

The basic syntax for an alias is:
alias SHORT_COMMAND='ORIGINAL_COMMAND'

- Example: alias ls='ls -lah'

## HOW TO INSTALL

1. git clone https://github.com/betnero/sobriquet
2. Copy the contents of the aliases.txt file.
3. sudo nano .bashrc
4. Paste the copied text below the contents of the .bashrc file.
5. To apply changes enter:
source ~/.bashrc 
OR
. ~/.bashrc

## HOW TO CONTRIBUTE

Check: CONTRIBUTING.md