# The "restore" command helps to unstage or even discard uncommitted local changes.

On the one hand, the command can be used to undo the effects of git add and unstage changes you have previously added to the Staging Area.

On the other hand, the restore command can also be used to discard local changes in a file, thereby restoring its last committed state.


`To only unstage a certain file and thereby undo a previous git add, you need to provide the --staged flag:`

> git restore --staged index.html

`You can of course also remove multiple files at once from the Staging Area:`

> git restore --staged *.css

`If you want to discard uncommitted local changes in a file, simply omit the --staged flag. Keep in mind, however, that you cannot undo this!`

> git restore index.html

`Another interesting use case is to restore a specific historic revision of a file:`

> git restore --source 7173808e index.html
> git restore --source master~2 index.html

The first example will restore the file as it was in commit #7173808e, while the second one will restore it as it was "two commits before the current tip of the master branch".

