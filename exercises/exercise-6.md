# This file contains exercise solution for altschool cloud engineering track (exercise 6). The following are outputs of these commands: 
- `git config -l` : This command lists all the configuration settings that have been set for a **git** installation. It shows both global and repository-specific configurations. The `-l` flag stands for "list".
 
- `git remote -v` : This command displays the remote repositories that your local Git repository is connected to. The `-v` flag stands for "verbose", which means it will show more detailed information, such as the URLs associated with each remote name.

- `git log` : This command shows the commit history in reverse chronological order (the most recent commits appear first). By default, it includes the commit hash, author, date, and commit message for each entry in the log.



## 1.  git config -l
user.name=Simeon Udoh
user.email=simeon.udoh45@gmail.com
core.repositoryformatversion=0
core.filemode=true
core.bare=false
core.logallrefupdates=true
remote.origin.url=git@github.com:0xSimeon/altschool-cloud-notes-and-exercises.git
remote.origin.fetch=+refs/heads/*:refs/remotes/origin/*
branch.main.remote=origin
branch.main.merge=refs/heads/main


## 2.  git remote -v

origin	git@github.com:0xSimeon/altschool-cloud-notes-and-exercises.git (fetch)
origin	git@github.com:0xSimeon/altschool-cloud-notes-and-exercises.git (push)

## 3.  git log
commit be51e7ba2de88bfeb455e6b475b380061e02f659
Author: Simeon Udoh <simeon.udoh45@gmail.com>
Date:   Wed Feb 7 03:52:39 2024 +0000

    :zap: add solution to first cloud assignment

commit 2d90d81e417065d702e31e50dea1b284eaf57b2a
Author: Simeon Udoh <simeon.udoh45@gmail.com>
Date:   Tue Jan 30 13:19:55 2024 +0100

    remove vim swap file

commit 61dcc35ebfb7115443e86e4e831ffb7409cb6845
Author: Simeon Udoh <simeon.udoh45@gmail.com>
Date:   Tue Jan 30 13:16:31 2024 +0100

    add more linux commands

commit 7f418f3b3f3ad630319eeb2ebc5410bd78e6e3d4
Author: Simeon Udoh <simeon.udoh45@gmail.com>
Date:   Thu Jan 25 21:19:28 2024 +0100

    add exercise 2

commit b5c965b357492785b9573de3d0997d9541049e7b
Author: Simeon Udoh <simeon.udoh45@gmail.com>
Date:   Sat Jan 20 05:16:57 2024 +0100

    add solution for exercise 1
