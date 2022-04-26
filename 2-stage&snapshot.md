1.  >git status

    `show modified files in working directory, staged for your next commit`

<br/>
<br/>

2. >git add [file]

    `add a file as it looks now to your next commit (stage)`

<br/>
<br/>

3. >git reset [file]

    `unstage a file while retaining the changes in working directory`

    <br> 

    * ## In this process the changes made to the files after last commit are not discarded, just the commit is removed from working flow
    
    <br>

    * >git reset --soft HEAD^

        `Moves the added files in last commit back to staged area`
    
    <br>

    
    * >git reset --soft HEAD^^


        `Discards last two commits and HEAD points two commits back`
    
    <br>
    
    * >git reset --soft HEAD~n


        `Discards last n commits and HEAD points n commits back`
    
    
    <br>

    * ## the changes made to the files in subsequent commits are lost

    <br>

    * >git reset --hard HEAD^ 

        `Move back to one commit earlier, Discarding Your Last Push ( Emergency only)`

<br/>
<br/>

4. >git diff

    `diff of what is changed but not staged`

<br/>
<br/>

5. >git diff --staged

    `diff of what is staged but not yet committed`

<br/>
<br/>

6. >git commit -m “[descriptive message]”

    `commit your staged content as a new commit snapshot`
    
    <br>

    * >git commit -a -m 'your commit message'
    
        `add & commit in a single command`