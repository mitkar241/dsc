# VCS
---

## Version Control System (VCS)
---
A Version Control System or VCS is a system that is capable of recording changes made to a file or a group of files over time. Git and Mercurial are two of the most popular version control systems. Important uses of a VCS are:

## VCS - need
---
- Check what was the last modification that caused a problem
- Compare the changes made over time
- Identifying who introduced a new issue and at what time
- Revert a file or files to some earlier state
- Revert the complete project to a previous state

## What Is Version Control and Why Should VCS Be Used
---
- Define version control and talk about how this system records any changes made to one or more files and saves them in a centralized repository. VCS tools will help you recall previous versions and perform the following:
- Go through the changes made over a period of time and check what works versus what doesn’t.
- Revert specific files or specific projects back to an older version.
- Examine issues or errors that have occurred due to a particular change
- Using VCS gives developers the flexibility to simultaneously work on a particular file and all modifications can be logically combined later.

## Revert a commit that has already been pushed and made public.
---
There are two ways of doing so:
- By creating a new commit to undo all changes made by the commit that has already been pushed and made public. Following command is used for doing so:
```
git revert
```
- By fixing or removing the bad file in a new commit and then pushing it to the remote repository. After making necessary changes to the file, commit it to the remote repository using the command:
```
git commit -m "commit message"
```

## git vs github
---

## git and SVN
---

## git rebase
---

## In Git how do you revert a commit that has already been pushed and made public?
---

## Describe a dev/test/production workflow using GIT
---

## Feature branching vs trunk based development
---

## Advantages of requiring pull requests and approvals
---
