### Try with release process

Step 1: we create a release branch (`feature/1.1.0`)

Step 2: we branch out from this release branch (`feature/1.1.0`)

Step 3: added code changes and commit

Step 4: merge PR (`feature/add-new-readme-file`) into current release branch (`feature/1.1.0`)

Step 5: merge (`feature/1.1.0`) back to `master` branch

Step 5.5: before create a new release branch, let do some changes and branch out from `master` branch

Step 6: branch out from `feature/1.2.0` to create a new branch called `feature/changes-only-for-1.2.0`

Step 7: make some changes to commit it and the open PR targeting for `feature/1.2.0` and then merge PR

Step 8: merge `feature/1.2.0` into master

