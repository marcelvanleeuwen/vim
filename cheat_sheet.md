# Vim Cheat Sheet

I made a cheat sheet with common Vim commands that I use often. It helps me remember the basics and work more efficiently when managing my homelab.

#### Vim command mode :
```sh
:d
```
Delete row
```sh
:u 
```
Undo
```sh
:wq
```
Saves edits and then exits Vim.
```sh
:%s/foo/bar/g
```

This is a substitution command.

- % — apply to all lines in the file
- s — substitute
- foo — the text to find
- bar — the replacement text
- g — globally on each line (replace all occurrences, not just the first)

#### Vim normal mode
```sh
!!{command}
```
Runs a shell command on the current line and replaces that line with the command’s output.
```sh
dd   
```
Delete row
