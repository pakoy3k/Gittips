
1. >git ls-files -s

    ` shows information about files in the index (the .git/index file) and the working tree`

2. >git remote show <remote_name>


    >>git remote show origin

    - list down all the remote branches and
    - know the mapping among local and remote branches
    - the impact of git pull and git push on local and remote branches
    - Sync status of each local branch with their corresponding remotes.
    

3. >git reflog

`Reflogs track when Git refs were updated in the local repository, show all HEAD reflog`

![gif_reflog](https://res.cloudinary.com/practicaldev/image/fetch/s--AS0ya8UC--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/rixan4h4z8y94eq89som.png)


4. >git blame [file]

`display of author metadata attached to specific committed lines in a file`

5. >git grep 

`Print lines matching a pattern`

6.  >git fetch --all 
    `First, run a fetch to update all origin/<branch> refs to latest` 
    >git branch backup-master
    `Backup your current branch`
    >git reset --hard origin/master
    `Force an overwrite of local files on a git pull`