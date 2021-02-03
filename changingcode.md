# Changing Code in Git

###Intro
There are various stages when updating code in a repository, and they are easy to mixed up. Before you continue you, it is important to understand some key terminology and the differences between these stages.

<!--TODO: insert picture of the lifecycle (save > add > commit > push)-->

The four different stages are:  

* **The Workspace**: Where you update the files in the editor of choice. You are used to just working in a workspace and saving files onto your device. Also refered to as your "working tree". The changes you make in this stage are refered to as `unstaged changes`
* **The Staging Index**: This is where you `add` changes that you are happy with, and are prepared to have incorporated in your repository. The changes you add to this staged are refered to `staged changes`
* **The Local Repository**: When you have completed a feature, or completed a certain task, your next step is to `commit` that change to your local repository. This is refering to the local copy of the repository you have on your device. A commit should have a meaningful message so that users can look back in their commit history and understand what each commit accomplished.
* **The Remote Repository**: When you want to move your local changes up to the main repostiory, you `push` these changes to the Remote Repository. This stage can come with issues (called `merge conflicts`) if other users have made changes at the same time as you and they conflict.

The arrows in the diagram show the commands you will use to move changes between the stages.


### Staged vs Unstaged
<!--TODO: How to unstage changes-->
<!--TODO: Git add (red if unstaged, green if staged). Meaning of "staged" and "unstaged"-->

### Stashing
<!--re stashing : 3 scenarios: 
1. You pull, you have unsaved changes (stash)
2. You pull, you've committed (merge conflict)
3. You pull, you have no changes or your commits are unrelated-->

## Commiting
<!--TODO: Get them to change something meaningful, not just their names-->
<!--TODO: talk about git diff to view changes-->

### Removing Changes
Depending on the situation, there are various ways you can remove changes or updates you've made. Here are some sample situations:

* You have unstaged changes **AND/OR** You have staged changes:  
`git reset --hard`
* You have staged changes you want to move back to being unstaged  
`git reset --mixed`
* You have some changes you want to keep, others you don't (this one is a little trickier)
* You want to remove a commit (move back in history)
* You want to work from a different stage in your commit history, but not lose the later commits


For more on resetting, have a look at [THIS](https://www.atlassian.com/git/tutorials/undoing-changes/git-reset) resource.

## Pushing

## Pulling
<!--TODO: talk about fetch vs pull. Fetch checks if there are changes to the repo, but doesn't apply anything. Pulling checks AND applies those changes straight away-->

<!--Merge Conflicts-->
<!--Stashing-->

## Conflicts
<!-- Force a conflict-->

<!--TODO: Maybe add a section on playing around with history?
https://stackoverflow.com/questions/10230469/temporarily-switch-working-copy-to-a-specific-git-commit/10230489#:~:text=First%2C%20use%20git%20log%20to,copy%20to%20a%20specific%20commit.-->

***[Next -> Getting Your Work Incorporated](incorporatingcode.md)***
