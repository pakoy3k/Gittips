> git log

`show the commit history for the currently active branch`

>git log branchB..branchA

`show the commits on branchA that are not on branchB`

>git log --follow [file]

`show the commits that changed file, even across renames`

>git diff branchB...branchA

`show the diff of what is in branchA that is not in branchB`

>git show [SHA]

`show any object in Git in human-readable format`

## TAG

>git tag -a [tag_name] -m 'tag message'
>>git tag -a v0.0.1-⍺ -m 'Published v0.0.1-⍺, need to stay awake to fix any bug 😭'

`creating a tag`

>git push --tags

`plublishing all tags`

>git push [remote] [tag_name]

`publishing a single tag`

>git tag || git tag -n

`list of all tags`

>git checkout [tag_name]

`check out a tag`

>git remote -v

`list of all remotes tags`


