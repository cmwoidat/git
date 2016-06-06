#Making a copy of a repo to work on locally
## Cloning

A **clone** is a local copy of a repository.  

`git clone [URL of your GitHub repo]`

This clones a remote repo to your local Git so you can begin to edit it. 

We will be using the New York Public Library's database for [Ian's databases workshop tomorrow](https://github.com/GCDigitalFellows/GCDRI_databases), so let's make a clone of it now.

`git clone https://github.com/GCDigitalFellows/GCDRI_databases`

Also, see if you can use the GUI on GitHub (just the buttons on the web page) to do the same thing. There should be a little "clone or download" button near the top right of each repo. 

## Pulling

If you receive an error notification that you are unable to push changes to your GitHub repo from your local repo, it often means that changes have been made to your GitHub repo that have not yet been logged locally. You'll have to pull the repo, then merge the changes by using `git commit -u origin master` (or whatever branch in which you're working) in order to return to smooth sailing with your `git push` commands. 

`git pull [URL of your GitHub repo]`

Remember, what you don't know can _always_ be Googled or looked up on Stack Overflow!  
___
[<<< Git add, commit, and push](gitaction.md) - [Return to repo](https://github.com/jentang/GitDRI)  
[Glossary](glossary.md) ~ ~ ~ [Helpful commands](helpfulcommands.md)