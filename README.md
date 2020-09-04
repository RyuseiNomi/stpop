# stpop

## About it

You can get help your git stash to be more useful by using this command!

This command can manipulate git stash operation as `git stash save`, `git stash pop` and more as interactive.

## Installation

You can get this command via homebrew

```
$ brew tap RyuseiNomi/tap
$ brew install RyuseiNomi/tap/stpop
```

## Usage

The command basicly start from `stpop` and you have to add any parameter.

```
$ stpop [parameter]
```

### Parameters

* `save` : You can save your current work. (equivalent with `git stash save`)
* `pop` : You can fetch your stashed work. (equivalent with `git stash pop`)
* `list` : A list of stashed work will be shown. (equivalent with `git stash list`)
* `show` : You can use it when you want to see the detail of stashed work. (equivalent with `git stash show`)
* `drop`: The command will drop the stashed work which you selected. (equivalent with `git stash drop`)

