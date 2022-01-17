### Try with release process

Step 1: we create a release branch (`feature/1.1.0`)

Step 2: we branch out from this release branch (`feature/1.1.0`)

Step 3: added code changes and commit

Step 4: merge PR (`feature/add-new-readme-file`) into current release branch (`feature/1.1.0`)

Step 5: merge (`feature/1.1.0`) back to `master` branch

Step 5.5: before create a new branch (`feature/changes-before-release-1.2.0`), let do some changes and branch out from `master` branch

Step 6: branch out from `feature/1.2.0` to create a new branch called `feature/changes-only-for-1.2.0`

Step 7: make some changes to commit it and the open PR targeting for `feature/1.2.0` and then merge PR

Step 8: merge `feature/1.2.0` into master


Step 9: after we merged `feature/changes-before-release-1.2.0` into `feature/release-1.3.0` branch, now we can branch out from `feature/release-1.3.0`

Step 10: now, we will make some `NEW` changes and merge into `feature/release-1.3.0`

Step 11: create a new branch `feature/changes-before-release-1.3.0` and make changes and then commit it.

Step 12: Now, we have merged `feature/changes-before-release-1.3.0` into `feature/release-1.4.0`, and then we branch out from `feature/release-1.4.0` to create a new branch called `feature/changes-only-for-1.4.0`

Step 13: add some changes from `feature/changes-only-for-1.4.0` and commit it and merge it into `feature/release-1.4.0`

Step 14: finally will merge `feature/release-1.4.0` into master branch

Step 15: today, the recall session has been completed 🎏🎏