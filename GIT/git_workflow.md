### [Source](https://www.freecodecamp.org/news/practical-git-and-git-workflows/)


# Purpose
 - To learn about advanced git concepts (branch, pull, fetch, merge, forking)
 - Cover the different git collaboration workflows available
 - Talk about communication as a TEAM and making the collaboration workflow work FOR you, rather than it hindering your work
 - Talk about solving Git conflicts


# Guidelines
 - There is no one sized fits all workflow
 - Short-lived branches
 - Minimize and simplify reverts
 - Match a release schedule


# Comparing Workflows
 - ### CENTRALIZED WORKFLOW
   - The easiest to implement
   - Working off one Github repo (Singluar POE)
 - ### FORKING WORKFLOW
   - Utilizes multiple Github repos
   - Requires good communication
   - Distributed workflow that is flexible (good for open source projects)

---
---

# Which Design to teach
 - CENTRALIZED WORKFLOW w/ Feature Branch Workflow
   - Making branches for features and then making pull requests in GitHub



# PART 1 => Git Demo (Branching, merging, .gitignore)
1. Talk about .gitignore file (purpose, template, etc)
2. Talk about branches (purpose, branching conventions)
3. Merge working branch with master branch
4. Delete old branch

```
git checkout -b <feature_branch>

git checkout <main or master branch>

git merge <feature_branch>

git branch -d <feature_branch>

```

# PART 2 => COLLABORATION Feature Branch Workflow / Centralized Repo (2-3 person)
1. Create a local project repo
2. Create Github repo and link together
3. Have two others clone Github repo
4. Have the other's clone repo, and create other branches
5. Add code to project and commit
6. 