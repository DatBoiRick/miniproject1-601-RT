# Git Terminology

- ### Repository
  * *Defintion:* A repository is the most basic element of GitHub. They're easiest to imagine as a project's folder. A repository contains all of the project files (including documentation), and stores each file's revision history. Repositories can have multiple collaborators and can be either public or private.
- ### Clone
  * *Definition:* A clone is a copy of a repository that lives on your computer instead of on a website's server somewhere, or the act of making that copy. When you make a clone, you can edit the files in your preferred editor and use Git to keep track of your changes without having to be online. The repository you cloned is still connected to the remote version so that you can push your local changes to the remote to keep them synced when you're online.
- ### Fork
  * *Definition:* A fork is a personal copy of another user's repository that lives on your account. Forks allow you to freely make changes to a project without affecting the original upstream repository. You can also open a pull request in the upstream repository and keep your fork synced with the latest changes since both repositories are still connected.
- ### Branch  
  * *Definition:* A branch is a parallel version of a repository. It is contained within the repository, but does not affect the primary or main branch allowing you to work freely without disrupting the "live" version. When you've made the changes you want to make, you can merge your branch back into the main branch to publish your changes.
- ### Commit  
  * *Definition:* A commit, or "revision", is an individual change to a file (or set of files). When you make a commit to save your work, Git creates a unique ID (a.k.a. the "SHA" or "hash") that allows you to keep record of the specific changes committed along with who made them and when. Commits usually contain a commit message which is a brief description of what changes were made.
- ### Merge    
  * *Definition:* Merging takes the changes from one branch (in the same repository or from a fork), and applies them into another. This often happens as a "pull request" (which can be thought of as a request to merge), or via the command line. A merge can be done through a pull request via the GitHub.com web interface if there are no conflicting changes, or can always be done via the command line.
- ### Checkout  
  * *Definition:* You can use `git checkout` on the command line to create a new branch, change your current working branch to a different branch, or even to switch to a different version of a file from a different branch with `git checkout [branchname] [path to file]`. The "checkout" action updates all or part of the working tree with a tree object or blob from the object database, and updates the index and **HEAD** if the whole working tree is pointing to a new branch.
- ### Push  
  * *Definition:* To push means to send your committed changes to a remote repository on GitHub.com. For instance, if you change something locally, you can push those changes so that others may access them.
- ### Pull  
  * *Definition:* Pull refers to when you are fetching in changes and merging them. For instance, if someone has edited the remote file you're both working on, you'll want to pull in those changes to your local copy so that it's up to date. See also fetch.
- ### Remote Add / Remove / Show  
  * *Remote Add:* will create a new connection record to a remote repository. After adding a remote, you'll be able to use as a convenient shortcut for in other Git commands.
  
  * *Remote Remove:* Use the `git remote rm` command to remove a remote URL from your repository.
 
  * *Remote Show:* Shows URLs of remote repositories when listing your current remote connections. By default, listing remote repositories only shows you their shortnames (e.g. "origin"). Using the `-v` option, you will also see the remote's URLs in listings.

- ### Status  
  * *Definition:* A visual representation within a pull request that your commits meet the conditions set for the repository you're contributing to.
- ### Master Branch  
  * *Definition:* The default branch in many Git repositories. By default, when you create a new Git repository on the command line a branch called `master` is created. Many tools now use an alternative name for the default branch. For example, when you create a new repository on GitHub the default branch is called `main`.







