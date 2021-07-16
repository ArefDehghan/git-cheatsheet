# git-cheatsheet

<i>1- Why do we use version control tools like Git?</i></br>
To maintain changes on a project's source and to make it possible for teams</br>
 to collaborate and work on the same project.</br>
  
<i>2- What is a repository and what files does a good repository have?</i></br>
A repository is where we store the source of a project and it's related files and</br>
it stores history of all the changes that we made on the sources and other source control related data,</br>
like branches, contributors, tags, etc.</br>
a good repository should have .gitignore, README, LICENSE files.</br>

<i>3- What components does a good document consists of?</i></br>
A good document should essentially describe the whys, whats and hows of the specified subject.</br>
  
<i>4- What does git clone command do?</i></br>
It gets the exact copy of the specified repository on your local machine.</br>
  
<i>5- What (Git) command do we use to get updates from remote repository into our local repository?</i></br>
git pull command.</br>
  
<i>6- What is the difference between reset, revert and checkout?</i></br>
checkout: git checkout is used for changing current branch.</br>
reset: git reset is used for undoing commits, it basically changes the HEAD of the branch.</br>
revert: git revert is used for undoing commits but the difference is that it does that using a new commit that</br>
inverts the changes to the specified commit and it doesn't remove the commit history.</br>
it's safer to use revert command instead of reset.</br>
     
<i>7- What is the difference between merge and rebase?</i></br>
merge: git merge keeps the commits history and merges two branches using a new commit.</br>
rebase: git rebase rewrites the history and adds the new commits on the tip of main branch.</br>
 
<i>8- What command do we use to see the commits history?</i></br>
git log command.</br>
  
<i>9- What command do we use to see the changes of a file?</i></br>
git diff.</br>
  
<i>10- What does tag used for and how can we create a tag?</i></br>
git tag <tag-name> is used for referencing a specific point in the history of our repository.</br>
tags are usually used for specifing the version of releases.</br>
  
<i>11- What is the process of contributing to a git project?</i></br>
We should fork the repository and push our changes on it and make a pull request.</br>

<i>12- What are branches used for and how can we merge them?</i></br>
Branches are used to separate the developing enviroment for different</br>
features, bug fixes and developers to keep the main branch stable and managed.</br>
We can merge branches using git merge and git rebase commands.</br>
