# Test Pull Request with Merge Conflict

## Purpose

Create a new branch, create conflicting changes to both it and main, then attempt to create a pull request to merge the branch to main.

## Process

1. Create local branch `test_pull_request_merge_conflict`
2. Create remote branch on origin
3. Create this file on the new branch and push
4. Create an incompatible copy of this file on main and push
5. Create a pull request between the new branch and main
6. Attempt to merge main into the new branch
7. Fix merge conflicts, commit, and push.
8. Merge pull request.

## Result

In progress.

## Lessons learned

- GitHub shows if the pull request can be automatically merged or not. If there is a conflict, it will still let you create the PR.
  - GitHub even lets you resolve conflicts in-browser.
  - VSCode has tools to help visualize and fix merge conflicts.
