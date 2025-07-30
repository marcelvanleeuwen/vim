# Vim Cheat Sheet

I made a cheat sheet with common Vim commands that I use often. It helps me remember the basics and work more efficiently when managing my homelab.

#### :Command mode
```sh
:d
```
Delete
```sh
:dd   
```
Delete row
```sh
:u 
```
Undo
```sh
:wq
```
saves edits and then exits Vim.
```sh
:%s/foo/bar/g
```
is a substitution command that means:

% — apply to all lines in the file
s — substitute
foo — the text to find
bar — the replacement text
g — globally on each line (replace all occurrences, not just the first)