# Purpose
 - Learn using Git / Github to collaborate
 - Learn about Merge Conflicts
 - Utilizing Feature Branch / Centralized Workflow, we can collaborate on a single project

# Resources
 - [Atlassian](https://www.atlassian.com/git/tutorials/syncing)
 - [Git Branching Game](https://learngitbranching.js.org/)


# Workflow
 - One person creates a Central Repository
 - Your team members are added as collaborators
 - Create branches locally to work on project and push to Github when ready
 - Remote branch will be merged with remote master branch(hopefully with no merge conflict)
 - The other collaborators will update their local master branch with the new code from the remote master branch

# Commands

## Basics
```
git branch -D BRANCH_NAME_HERE

git pull origin master/main
```