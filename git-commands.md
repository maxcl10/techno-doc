# Git commands

Here is the documentation of the git commands <https://git-scm.com/docs>.

## List all remote branches

```console
git branch -r
```

## Checkout a remote branch

```console
git checkout feature/customer-preferences/
git checkout origin/… --track
```

## Delete a local branch

```console
git branch -d -r <branch-name>
```

-r delete remote-tracking branches.

## Get the origin version and override the local changes

```console
git reset --hard origin/branch-name
git reset --hard origin/main
```

## Remove all stale remote branch

```console
git remote prune origin
```

## Push and set and create an origin branch

```console
git push --set-upstream origin bugFix/send-ref-code
git push -u origin bugFix/send-ref-code
```

If the branch has the same name

```console
git push -u origin HEAD
```

## To untrack a tracked file

```console
git rm -r --cached .vs/
```
