1. > git log

    `show the commit history for the currently active branch`

    >>git log branchB..branchA

    `show the commits on branchA that are not on branchB`

    >>git log --follow [file]

    `show the commits that changed file, even across renames`

<br/><br/>

2. >git diff branchB...branchA

    `show the diff of what is in branchA that is not in branchB`

<br/><br/>

3. >git show [SHA]

    `show any object in Git in human-readable format`

<br/><br/>

## TAG
<br/>

>git tag -a [tag_name] -m 'tag message'
>>git tag -a v0.0.1-⍺ -m 'Published v0.0.1-⍺, need to stay awake to fix any bug 😭'

`creating a tag`

<br/>

>>git push --tags

`plublishing all tags`

<br/>

>>git push [remote] [tag_name]

`publishing a single tag`

<br/>

>>git tag || git tag -n

`list of all tags`

<br/>

>>git checkout [tag_name]

`check out a tag`

<br/>

>>git remote -v

`list of all remotes tags`


