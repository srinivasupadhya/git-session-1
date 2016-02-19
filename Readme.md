* *Getting Started with git*

`git clone <url>` / `git init .`

`git status`

* *History of changes*

`git log`

`git show <commitid>`

```
git log -<limit>
git log -p
git log --author="<pattern>"
git log --grep="<pattern>"
git log <since>..<until>
```

`git show <commit>`

`git blame <file>`

* *Local commits*

`git diff`

`git add` / `git mv` / `git rm`

`git diff --staged`

`git reset <file>`

```
git reset --soft <commit-sha>
git reset --hard <commit-sha>
```

`git commit -m "<message>"`

`git push origin <branch-name>`

`git stash`

```
git stash save
git stash list
git stash show -p stash@{0}
git stash apply
git stash drop
```

`git format-patch <commit-sha>`

`git apply <patch-file>` / `git am <patch-file>`

* *Branching*

`git branch`

`git checkout <branch-name>`

`git fetch <branch-name>`

`git merge <branch-name>`

`git pull <branch-name>`

`git cherry-pick <commit-sha>`

`git rebase <branch-name>`

`git branch -d <branch-name>`

* *Miscellaneous*

