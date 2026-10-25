\# My Git Journey — Nanu's Recipe Book



\## 1. My Story



I created a recipe repository for Nanu's Khata and practiced Git commands to manage recipes, branches, commits, and remote changes. Mitu cloned the repository and added the Chittagong Mezban recipe.



\## 2. Commands Practiced



\- `git config --global` — configured Git identity.

\- `git branch` and `git switch` — created and switched branches.

\- `git add` and `git commit` — saved meaningful changes.

\- `git push`, `git fetch`, `git merge`, and `git pull` — practiced sharing and receiving changes.

\- `git stash` and `git stash pop` — temporarily saved and restored unfinished Halua work.

\- `git mv` — moved recipes into a folder.

\- `git rm` — deleted an old recipe.

\- `git log --stat -M` — inspected commit changes and rename detection.

\- `git show` — inspected a selected commit.

\- `git reset --hard` — practiced on a test branch, not on main.



\## 3. Key Screenshots



Insert screenshots showing:

1\. Meaningful commit history and at least two branches.

2\. The stash, Biryani commit, and restored Halua work.

3\. Recipe organization using `git mv` and `git rm`.

4\. `git log --stat -M` and `git show`.



\## 4. Theory Answer



Rebase can rewrite commit history, and `git reset --hard` can move a branch backwards and discard uncommitted tracked changes. On a shared branch, these operations can disrupt collaborators and cause history conflicts. `git revert` is generally safer for undoing shared commits because it creates a new commit.



\## 5. Final Git History



Attach the final screenshot of:



`git log --oneline --graph --all`



