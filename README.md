# This is git recalls repository (for concepts understanding)

### 1. `cherry-pick`

Explanations:

We have 3 commits in cherry-A branch

We have 1 commit in cherry-B branch

Now, we want put cherry-A's <mark>3rd</mark> commit into cherry-B branch

command:

```shell
# 1st step: go to cherry-B branch
# 2nd step type command below: 
git cherry-pick `3rd-commit-hash-value`
# or we can use `-n`: which means cherry-pick the commit contents but NOT create a commit immediately (keep the file in the staged status) 
git cherry-pick `3rd-commit-hash-value` -n
# Done
```
### 2. `submodules` related commands

