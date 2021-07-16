# git-cheatsheet

1-
  Q: Why do we use version control tools like Git?
  A: To maintain changes on a project's source and to make it possible for teams
     to collaborate and work on the same project.
  
2-
  Q: What is a repository and what files does a good repository have?
  A: A repository is where we store the source of a project and it's related files and 
     it stores history of all the changes that we made on the sources and other source control related data,
     like branches, contributors, tags, etc.
     a good repository should have .gitignore, README, LICENSE files.

3-
  Q: What components does a good document consists of?
  A: A good document should essentially describe the whys, whats and hows of the specified subject.
  
4-
  Q: What does git clone command do?
  A: It gets the exact copy of the specified repository on your local machine.
  
5-
  Q: What (Git) command do we use to get updates from remote repository into our local repository?
  A: git pull command.
  
6-
  Q: What is the difference between reset, revert and checkout?
  A: checkout: git checkout is used for changing current branch. 
     reset: git reset is used for undoing commits, it basically changes the HEAD of the branch.
     revert: git revert is used for undoing commits but the difference is that it does that using a new commit that 
     inverts the changes to the specified commit and it doesn't remove the commit history. 
     it's safer to use revert command instead of reset.
     
  
7-
  Q: What is the difference between merge and rebase?
  A: merge: git merge keeps the commits history and merges two branches using a new commit.
     rebase: git rebase rewrites the history and adds the new commits on the tip of main branch.
     
8- 
  Q: What command do we use to see the commits history?
  A: git log command.
  
9-
  Q: What command do we use to see the changes of a file?
  A: git diff.
  
10-
  Q: What does tag used for and how can we create a tag?
  A: git tag <tag-name> is used for referencing a specific point in the history of our repository.
     tags are usually used for specifing the version of releases.
  
11-
  Q: What is the process of contributing to a git project?
  A: We should fork the repository and push our changes on it and make a pull request.

12-
  Q: What are branches used for and how can we merge them?
  A: Branches are used to separate the developing enviroment for different 
     features, bug fixes and developers to keep the main branch stable and managed.
     We can merge branches using git merge and git rebase commands.
 
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
