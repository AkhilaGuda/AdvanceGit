1. Cherry-Picking

    Created a new branch , two feature branches , performed commits and cherry-pick a specific commit from another branch.

    Commands Used:

    git checkout -b feature-branch
    To check commit hash : git log --oneline
    git cherry-pick <commit-hash>

3. Stashing and Cleaning

    Temporarily stash changes and clean the working directory.

    Commands Used:

    git stash or git stash push
    git stash list
    git stash apply
    git stash drop
    git stash apply stash@{index}
    git stash pop (apply +drop)

5. Interactive Staging

    Use interactive staging to stage portions of changes.

    Command Used:

    git add -i

6. Undoing Changes

  Revert a commit to undo its changes.

    Commands Used:
    git commit -m "changes"
    git revert <commit-hash>

5. Git Reset

   Move the HEAD pointer to a previous commit.

    Command Used:
   git reset  <commit-hash> (mixed reset brings the changed files onto )
    git reset --soft <commit-hash>
    git reset --hard <commit-hash>

7. Git Show

    View detailed information about a specific commit.

    Command Used:

    git show <commit-hash>

8. Rebasing

   Interactive rebase and squash commits.

    Command Used:

    git rebase -i HEAD~<number>

9. Reflog

    Recover a lost commit using reflog.

    Commands Used:

    git reflog
    git checkout <commit-hash>
