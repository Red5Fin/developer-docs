# Developer Docs

## Git Flow

Before start working - check branch - `git branch`

if not develop, do - `git checkout develop`

if develop -
 
Decide what you are working on, For eg. Gallery

Check branch on local machine,

Create a new  branch (while being on develop branch) - `git branch feature/gallery`

### Command breakdown - `git branch {branchname}`

* if you are adding something new, branch name will be - `feature/{task}`
* if you are fixing something, branch name will be - `hotfix/{fixedtaskname}`
* if you are redesigning something - `redesign/{task}`

**IMP - Once you create a branch**

`git checkout {branchname}`

**Now start your work, once work is done  -**

`git add --all`

`git commit -m "Changes which you made"`

`git push`

**_Git push will give an error in console for first time and tell you to create upstream, it will provide the code just copy paste_**

Example - `git push --set-upstream origin {branchname}`

_After git push, for the first time, you will have to create a Pull Request_

you will get a URL in the console, Ctrl + Click the link and write Task in Title and description describing your PR 

Your Pull request will be reviewed, approved and merged by the team members.
