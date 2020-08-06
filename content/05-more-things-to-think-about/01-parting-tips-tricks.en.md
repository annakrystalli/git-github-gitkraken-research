---
title: Parting Tips & Tricks
weight: 6
---


## Revert a commit

Imagine you've made a mistake, and committed something you didn't intend to - maybe code that broke everything, or you added a file you didn't intend to add. You can revert commits - 

in GitKraken, try right clicking on the commit in the history panel. You'll have to commit the revert - it doesn't erase the

## Ignore files

Sometimes there are files you don't want to commit to your repository. Examples might be:
- the `.DS_Store` file automatically generated on Mac systems, 
- files that contain sensitive information 
- large files (> 5MB) or autosave backup files that some text generators add. 

Such files can be excluded from showing up as modified if they are included in a **.gitignore** file,. [More information about using `.gitignore`](https://www.atlassian.com/git/tutorials/saving-changes/gitignore).

## A few more things

- **Command line** - there are a lot of other commands you can use with Git. If you're feeling brave,
- **Git Branching** - if you're working on more than one thing at once, you can create a separate [branch](https://www.atlassian.com/git/tutorials/using-branches) for each bit of work. This guide uses Git on the command line.

