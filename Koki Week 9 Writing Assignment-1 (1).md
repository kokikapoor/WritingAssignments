## Koki Kapoor 
## Week 9 Writing Assignment 
## CSC 630
## Due: Friday, November 13, 2020
&nbsp;

Prompt: Learn about and write about more challenging aspects of git that we haven't covered, such as rebase, tags/releases, stash, or squash, to name a few.   
**Today's Focus: GIT REBASE**
&nbsp;

> Git Rebase: *Rebase* and *Merge* are 2 Git utilities that are useful for branch integration. However there are several distinctions and nuances that make these 2 utilities vastly different. The merge command, for example, allows you to combine, or “merge”, two branches, such as the main and feature branch, the main and secondary branch, etc. It, without any major change or destruction of code, ties together the histories of these branches with a common end-point. One of the downfalls of the *Merge* command is that it creates a polluted and scattered project history with extra commits and messages. The *Rebase* utility, on the other hand, not only incorporates all the commits of the feature/secondary branch by moving it to the tip of the master branch but also keeps the code neat and organized and maintains a linear and cleaner project history that is easy to visualize using a simple “git log” command line. Rebase can also be used to permanently delete files from a codebase, library, or repository. There is a special kind of rebasing known as *Interactive Rebasing* that allows the coder to work on and “polish” the aspects of a feature/secondary branch by deleting extraneous commits, unnecessary code, obsolete/redundant command lines, before committing to creating a git log that is organized, neat, and linear. Basically, this Interactive Rebasing allows you to change and alter commits as they are being moved to the main branch, signifying that the coder has full authority and control over the code. It is important to understand that when implementing a command as powerful as Git Rebase, there will undoubtedly be some major dangers that can break the project or library. First, merge conflicts may pop up more often than usual if one of the branches is not frequently updated and is far ahead of the other branch. Other issues could arise when important commits are mistakenly lost while partaking in interactive rebasing, which removes all extraneous commits but may also result in the loss of necessary and crucial ones. All in all, however, Git Rebase is an extremely important tool and when used appropriately and correctly, can aid in creating an organized, well-presented codebase. 

``` python 
git rebase
git rebase --interactive
```

Citations:   
[Atlassian BitBucket Article 1](https://www.atlassian.com/git/tutorials/rewriting-history/git-rebase#:~:text=Rebase%20is%20one%20of%20two,has%20powerful%20history%20rewriting%20features.)   
[Atlassian BitBucket Article 1](https://www.atlassian.com/git/tutorials/merging-vs-rebasing)   
[Tiny Cloud Article](https://about.tiny.cloud/blog/the-advanced-git-guide-git-stash-reset-rebase-and-more/)   
