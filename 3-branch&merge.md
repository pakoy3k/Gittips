1. >git branch

    `list your branches. a * will appear next to the currently active branch`

<br><br>

2. >git branch [branch-name]

    `create a new branch at the current commit`

    <br>

    * >git branch -a

        `Shows remote and local branches`

    <br>

    * >git branch

        `Shows only local branches`

    <br>

    * >git branch -d [branch_name] 

        `Deleting a local feature branch, forcefully using -D`

    <br>

    * >git push -d [remote_name][branch] 

        `Deleting a remote branch`

    <br>

3. >git checkout [branch_name]

    `switch to another branch and check it out into your working directory`
    
    <br>

    * >git checkout -- <path_to_file>
        
        `Discarding changes made on a file`
    
    <br>

    * >git checkout -b [branch_name]
        
        `Creating and checking in with a single line`

<br>

4. >git merge [branch]

    `merge the specified branch’s history into the current one`

<br><br>

5. >git log

    `show all commits in the current branch’s history`

<br><br>

6. >git worktree

    `Manage multiple working trees attached to the same repository.`

    <br/>

    >>git worktree add [path_directory][branch_name]

    `create path_directory and checkout branch_name into it`

    >>git worktree list 

    `list details of each worktree`