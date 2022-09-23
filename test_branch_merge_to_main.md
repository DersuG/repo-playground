# Test Branch Merge to Main

## Purpose

Merge a local branch containing new files to main.

## Process

1. Create branch `branch_test` (`git branch branch_test`)
2. Checkout branch (`git checkout branch_test`)
3. Create `test_branch_merge_to_main.md`
4. Stage (`git add test_branch_merge_to_main.md`)
5. Commit (`git commit -m "Test branch merge to main."`)
6. Create and push to remote branch (`git push --set-upstream origin branch_test`)
7. Switch to main branch (`git checkout main`)
8. Merge `branch_test` to main (`git merge branch_test`)
9. Delete local `branch_test` (`git branch -d branch_test`)
10. Delete remote `branch_test` (`git push origin -d branch_test`)

## Result

Success.