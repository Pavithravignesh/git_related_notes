1. 
we don't mutate the state in action fn(), while using vanialla redux and you have to return
in reduxToolkit, actually you have to mutate the to work with the action fn(), inside to reducers at the slice, here you don't have to return any,

And for special mention, nothing has eliminated here, but reduxTool kit does it with immer library

every simply, it's all how to deep copy a obj and making the change over there?

a feature/bug - create separate branch and create PR, once done, follows as to another,

2. 
every branch for each feature/bug, and following create PR as for each branch!

00:00 - 25:25 --> I'm here

25:25 - 37:31

undo the add: git restore --staged <file name>

remove the commit: git reset <commit hash>

/** stash **/ 

- right after the git add .

- git stash

- put in somewhere, whenever i need it back I can get it. however without committing it! JUST put IT SOMEWHERE!

- just stage them, and put it stash

- /* to get the stashed data back */

- git stash pop

- /* to make the data clear */

- git stash clear


/** why branch? **/
- 

/** why fork? **/
- making copy of someone elses remote to you're remote, which make do change in the copyied remote at you're own account which won't be affecting the original one,
- forked repo also can be merged with the original repo, from the end who own the original repo,

/** whaat is origin and how to find what could be the origin for the repo i've been working on? **/
- what is the account name placed followed by repo.git in the clone URL, that's the origin account which having the original repo, and that's the origin
- if the cloning URL has you're account name at the starting, which is before the repo.git, then it's at your account.

/** what upstream? **/
- original repo from where I've made fork from,

/** origin is my forked copy of someone elses, and upstream is the repo from where I've made the fork **/

whatever the changes you made in you're feature-branch at you're local, should be there in the remote's main branch, Right? - BIG YESSSSS!

/** what PR? **/
- Pull request to merge my code from my local feature-branch to remote main,
- which has to be from local feature to remote's feature-branch

git add .
git commit -m "something"

git checkout main
git pull origin main

git checkout feature-branch
git rebase main

git push origin main

PR will be create according,

if you're merging it, then it will be merge you're local code with remote main, as how you're made the PR,

now, what are git rebase main and rebase and merge does?


/** removing commit form the PR by force pushing ti to, **/
- git reset <hash> which get you that particulat commit,
- and run force push on that commit, since the last commit only will be there in the remote, not at yours
git push origin feature-branch -f


?
1. what does git rebase main does?
2. what does rebase and merge does?
3. how to restrict original repo from forked repo?



# 3 nothing from here
# added for this
# added for this

# 4 nothing from here
# added for this
# added for this