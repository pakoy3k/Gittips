1. >git remote add [alias] [url]

    `add a git URL as an alias`

    <br>
    
    * >git remote -v

        `list of all remote repositories that are currently connected to your local repository`

    <br>
    
    * >git remote add production_aws https://pako@github.com/pako/example_aws.git

        `add a new remote repository`

<br><br>

2. >git fetch [alias]

    `fetch down all the branches from that Git remote`

<br><br>

3. >git merge [alias]/[branch]

    `merge a remote branch into your current branch to bring it up to date`

<br><br>

4. >git push

    `git pushes committed changes to all remote branches which are tracked`

    <br>

    * >git push [remote] [branch_local]
        >>git push bitbucket feat/dune/login_api

        `Transmit local branch commits to the remote repository branch,`

    <br>

    * >git push -f

        `Push the commit forcefully to remote`

<br>

5. >git pull

    `fetch and merge any commits from the tracking remote branch, git pull is a two step process`
    
        - ***git fetch*** fetches the remote branches
        - ***git merge FETCH-HEAD*** and merges the locals with the latest HEAD available for each branch.

     <br>

    * >git pull [remote] [remote-branch-name]
    
    * >> git pull origin feat/dune/address_management

        `Pull down a single branch only`


