### **Git hooks** are scripts that run automatically every time a particular event occurs in a Git repository. They let you customize Git’s internal behavior and trigger customizable actions at key points in the development life cycle.

![img_git_hooks](https://wac-cdn.atlassian.com/dam/jcr:ac22adee-d740-4216-a92a-33c14b5623e5/01.svg?cdnVersion=319)

Hooks reside in the .git/hooks directory of every Git repository. The built-in scripts are mostly shell and PERL scripts, but you can use any scripting language you like as long as it can be run as an executable. The shebang line (#!/bin/sh) in each script defines how your file should be interpreted. So, to use a different language, all you have to do is change it to the path of your interpreter.



![](https://user-images.githubusercontent.com/300046/38129418-3643b1dc-33bc-11e8-8d3d-37fd0ea72ade.jpg)

 
>mv .git/hooks/pre-commit.sample .git/hooks/pre-commit

>vim .git/hooks/pre-commit

```sh 

#!/bin/sh
#This hooks is for notification in telegram group about all commits
rama=$(git status | grep Your)
author=$(git show | grep Author)
info=$(git log --name-status HEAD^..HEAD)
echo $rama
echo $author
echo $info
url="https://api.telegram.org/bot32:ID_BOT/sendMessage"
curl -s -X POST $url -d chat_id=ID_TELEGRAM_GROUP -d text="$info"
echo $url
```