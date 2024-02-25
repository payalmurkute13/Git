1. What is Git?


        
 Git is a distributed version control system designed to handle everything from small to very large projects with speed and efficiency. It allows multiple developers to work together on the same project simultaneously, providing tools to manage the changes to source code and other files. Git tracks the history of changes, enabling developers to revert to previous versions, compare changes over time, and collaborate with others with minimal conflicts.


2. How do you revert a commit in Git?
   
 To revert a commit in Git, you can use the git revert command followed by the commit's hash. This command creates a new commit that undoes the changes made by the specified commit, preserving the project history. This is a safe way to undo changes in a shared repository.

Example:

    git revert <commit-hash>

 3. What is a branch in Git?
     How do you create and switch to a new branch?
    
 A branch in Git is essentially a pointer to a snapshot of your changes. 
 
 To create a new branch, you use the git branch command followed by the name of the new branch. To switch to a new branch, you use the git checkout command followed by the name of the branch.

     git branch new-feature
     git checkout new-feature

 Alternatively, you can combine these steps with:
 
      git checkout -b new-feature

 4. What is a 'pull request' in Git?
    
 A pull request is a method of submitting contributions to a project. It is specific to platforms that host Git repositories, like GitHub. A pull request is raised by a developer to request that their changes be pulled into another branch or repository. It provides a platform for discussing the proposed changes, reviewing code, and making further modifications before the changes are merged into the base branch.



5. How do you stash changes in Git?
   
 Stashing in Git temporarily shelves (or stashes) changes so that you can work on a different task. Your working directory is then reverted to match the HEAD commit. The command for stashing is:

     'git stash'

 You can later reapply the stashed changes with:

    git stash pop
    
