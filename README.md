# README.md

## What is this? 
Small list of `argument-less` shell helpers to manage interaction with git repos, like update or remove branches locally & remote, keep master update to date 


## Inspiration 
get annoying by typing every day same kind of command-sets to manage git repos in daily business
got inspired by https://stackoverflow.com/questions/45352246/how-to-switch-and-save-without-commit-in-git
and wrote small bash helpers which helps me to manage my git repos with `argument-less`* helpers
*gbrm requires one argument

## Installation
- clone / download repo to a folder of your choice
- add the bin folder to your list of paths, e.g. by updating your .bashrc: 
`export PATH=$PATH:<checkout-path>/bin`
e.g. `export PATH=$PATH:/Users/Saparot/Projects/Saparot/gitShellHelper/bin`

## Helper overview

## `gbru` git branch rebase update
- save your local changes by temporary local commit local 
- switch to master, updater it from upstream
- switch to branch you called `gbru` from, rebase it from master
- restore your local changes by reverting local commit
- just continue in the branch you are working..

### `gbrm` git branch remove
- remove branch `local` and push remove to `origin`

### `gbs` git branch switch
- save changes by temporary local commit in current branch
- switch to the branch you asked for and restore changes stored in the request branch

### `gmu` git master update
- works only when you are in master 
- save your local changes by temporary local commit local 
- pull from upstream 
- restore your local changes by reverting local commit

### `gtlc` git temporary local commit
- save your local changes by temporary local commit local 

### `gtlr` git temporary local restore
- restore your local changes by reverting local commit


