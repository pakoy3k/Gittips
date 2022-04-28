### git stash temporarily shelves (or stashes) changes you've made to your working copy so you can work on something else, and then come back and re-apply them later on. Stashing is handy if you need to quickly switch context and work on something else, but you're mid-way through a code change and aren't quite ready to commit.

<div style="background-color:white">

![img_stash_flow](https://w3cschoool.com/public/file/GitHub/git-stash.png)
</div>

1. >git stash

    `Save modified and staged changes`
    <br><br>
    
    >>git stash -u

    `-u option (or --include-untracked) tells git stash to also stash your untracked files`
    <br><br>
    
    >>git stash save "text"

    `add description to stash`
    <br><br>
    
    >>git stash list

    `list stack-order of stashed file changes`
    <br><br>
    
    >>git stash pop

    `write working from top of stash stack`
    <br><br>
    
    >>git stash drop

    `discard the changes from top of stash stack`
    <br><br>
    
    >>git stash apply

    `reapply the changes to your working copy and keep them in your stash`
    <br><br>

    >>git stash show | git stash show -p

    `view summary of a stash | view the full diff of a stash`
    <br><br>

    >>git stash branch add-stylesheet stash@{1}

    `create a branch from a stash`
    <br><br>

    >>git stash clear

        `delete all stashes`