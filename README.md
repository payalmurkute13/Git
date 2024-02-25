# Git
git command and some key points

Sure, let's break down Git into simpler terms and explain the basic commands you'll use most often. Git is a version control system that helps you keep track of changes to your files and collaborate with others. It's like a save point system for your project, allowing you to revert back to previous states and merge changes from different sources.

1. Starting with Git
 
* git init: This command initializes a new Git repository. It's like setting up a new project folder 
   that Git will track.

        git init

* git clone [url]: Copies an existing Git repository from a remote location (like GitHub) to your 
  local machine.

       git clone https://github.com/example/repo.git

 2. Working on Your Project

* git status: Tells you what's going on in your repository. It shows which files have changed, which 
   are ready to be committed, and which are not being tracked by Git.

        git status
    
* git add [file]: Adds files to the staging area. It's like telling Git, "Okay, I'm ready to save 
    these changes."

      git add myfile.txt
    
* To add all changed files, you can use:

       git add .
    
* git commit -m "[message]": Saves your changes to the local repository. Think of it as creating a save point in your project.

      git commit -m "Fixed the bug causing crashes"

3. Viewing Changes
4. 
* git log: Shows a history of commits. It's like looking through your project's timeline.

      git log
  
* git diff: Lets you see the differences between your current files and the last commit. It's useful 
  for checking what you've changed.

      git diff

4. Branching and Merging
   
* git branch: Lists all the branches in your repository or creates a new one.

      git branch new-feature

* git checkout [branch-name]: Switches to another branch. It's like moving to a different version of 
   your project.

      git checkout new-feature
  
* To create and switch in one command:

      git checkout -b new-feature
  
* git merge [branch]: Merges changes from one branch into another. It's like combining the changes 
   from different versions of your project.

      git merge new-feature
5. Working with Remote Repositories

* git remote add origin [url]: Links your local repository to a remote server. Useful for setting up 
  a connection to GitHub or another online repository.

      git remote add origin https://github.com/example/repo.git
  
* git push -u origin [branch]: Sends your commits to the remote repository. It's like uploading your 
  save points so others can see or contribute.
  
      git push -u origin main
  
* git pull: Fetches updates from the remote repository and merges them into your local repository. 
  It's like downloading the latest version of the project.

      git pull
    

    
