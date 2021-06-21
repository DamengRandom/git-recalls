# This is git recalls repository (for concepts understanding)

### 1. `cherry-pick`

<strong>Explanations:</strong>

We have 3 commits in `cherry-A` branch

We have 1 commit in `cherry-B` branch

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

Reference <a href="https://www.youtube.com/watch?v=wIY824wWpu4" target="_blank">here</a>


### 2. `submodules` related commands

`git submodules`: allows developer to keep a git repository as subdirectory of another git repository (Its a snapshot of another repository)

Common command:

```shell
# Example: In your current project, you can create submodule of another project
git submodule add https://github.com/DamengRandom/git-recalls.git
```

<mark>Why</mark> we need git submodules: Assuming that when you have a project in git which depends on `a particular versions` of other projects
