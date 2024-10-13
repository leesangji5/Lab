# Git

### __Version control__

__Local__: Collaboration is impossible

__centralized__: Managed by central vcs server, If the central server is down, you can't do it.

__Distributed__: Distributed storage is also implemented to compensate for the shortcomings of centralized storage. like merge an local, centralized.

__State__: has three states in git
 * working directory: The location where your current project files are stored locally, and where you work on and modify files
 * staging area: A temporary area where files are stored after using the git add command to prepare them for a commit
 * git directory: The .git folder that stores all metadata and history of the project

__installing git__

`git --version`

`sudo apt install git-all #if has un error in git --version`

__git config__
 * system level: --system option. affects all uses
 * global level: --global option. affects all repositories
 * local level: --local option. specific to the current repository

` git config --global user.name "leesangji"`

`git config --global user.email myemail@gachon.ac.kr`

`git config --global init.defualtbBranch main`

`git config --list`

`git config --list --show-origin`

`git config user.name`
