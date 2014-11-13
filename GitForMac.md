# Repository Basics

Below are some notes that I'm writing as I'm in the process of learning how to use GitHub Repositories. I'll also put a link to a screen-cast covering these same topics. Please feel free to add to this. The general goal is to be able to make use of Git in simple and effective ways.

Here's the screen cast. 

https://dl.dropboxusercontent.com/u/14462007/Videos/GitHubBasics.mov

### Note the branching functionality is very important. I did not describe this in the screencast, but see below.


## Get this stuff first

1. Get a GitHub account, it's free
2. Download GitHub for Mac, it's a free program for easy sharing between repositories on Github, and repositories on your local machine.

## Creating a repository from the GitHub webpage

1. Go to your user page on GitHub, click on the Repositories Tab, click the big green New Button. Give the new repository a name. You're done. You can add new text files directly through the web by following similar steps.

The new repository can now be expanded in various ways. You can clone a copy of it onto your local machine. You can make changes to the files on your (and of course add new files), then push those changes back onto the cloud version (which could be the gold-standard version of the files in the repository). All of the changes will be tracked and recorded.

## Cloning a repository from the GitHub Webpage onto your local machine.

1. Download Github for Mac (there ought to be some linux or windows equivalent?).
2. Enter your GitHub user info in the preferences
3. Click the "+" sign  on the top left corner. This let's you do different things like add, create and clone. Choose clone.
4. If you have existing repositories in your user account (for example, you made a test repo using via the webpage), then this repo should show up. Simply click the repo you want to clone, then name a folder where you want the clone to reside. Now, the entire repository will be in that folder on your local machine.

## Syncing the local folder back to the GitHub cloud 
1. If you have successfully cloned a repository, then you can just go to that folder and work on the files in that folder in the way you normally would. Open the files, make changes, add new files etc.
2. When you want to resync the changes that you made on your local machine to the cloud version of the repo, open up GitHub for Mac, click on the name of the repo that you have been working on, simply press the sync button on the top right-hand corner (you can also make a note to yourself if you want about the nature of the changes that were made by clicking on the changes tab before you sync and writing the note).

## Creating a repository locally using Github for Mac and sending it GitHub 

1. Have some folder that you want to turn into a Git Repo
2. Open Git for Mac
3. Press the add button, choose Add, choose the folder containing the files for your repo.
4. Choose Create and Add
5. When you are ready, sync the repo to GitHub. You will be able to choose where the repo goes (e.g., your own Github page, or any other one where you have privileges, like CogPsyDraftTable).


# Branching and collaborating with Repositories

Github repositories can have a branching structure, with a master branch and sub-branches. Branching is very useful for collaboratively working on a project. It allows collaborators to create a branch off of the master, make changes to the branch, and then merge the changes at the branch level up to the master level. This works well for software development, where the master level is intended to contain code that is always verified to work. In this context it could be dangerous to edit the master branch directly because edits could corrupt the stability of the master code. Using branches, changes can be made to a copy of the master, the collaborator can test the changes at the branch level to make sure there are no issues, then they can send the edited branch back to the master repository. This would constitute making a pull request. Then, at the master branch level, the incoming edits (the pull request) can be reviewed and commented upon, and finally merged into the main master branch.


###Help on using branches

https://help.github.com/articles/branching-out/











