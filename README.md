\*\* Bundle 2 Exercise 1

```
walte@Walter MINGW64 ~
$ source .bash_profile

walte@Walter MINGW64 ~
$ cd d:

walte@Walter MINGW64 /d
$ cd Fi
Final-Git-Practice/    Fix_My_Code_Challenge/

walte@Walter MINGW64 /d
$ cd Final-Git-Practice/

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

walte@Walter MINGW64 /d/Final-Git-Practice (ft/bundle-2)
$ vi services.html

walte@Walter MINGW64 /d/Final-Git-Practice (ft/bundle-2)
$ add
warning: in the working copy of 'services.html', LF will be replaced by CRLF the next time Git touches it
[ft/bundle-2 db2bbce] Latest Update
 1 file changed, 12 insertions(+)
 create mode 100644 services.html
fatal: The current branch ft/bundle-2 has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/bundle-2

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


walte@Walter MINGW64 /d/Final-Git-Practice (ft/bundle-2)
$ git push origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 544 bytes | 544.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/AristideI/Final-Git-Practice/pull/new/ft/bundle-2
remote:
To https://github.com/AristideI/Final-Git-Practice.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2

walte@Walter MINGW64 /d/Final-Git-Practice (ft/bundle-2)
$
```

```


walte@Walter MINGW64 /d/Final-Git-Practice (ft/bundle-2)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ git checkout -m ft/service-redesign
error: pathspec 'ft/service-redesign' did not match any file(s) known to git

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

walte@Walter MINGW64 /d/Final-Git-Practice (ft/service-redesign)
$ ls
2  file  file2  fileone.html

walte@Walter MINGW64 /d/Final-Git-Practice (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ ls
2  file  file2  fileone.html

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ git pull
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (1/1), 625 bytes | 312.00 KiB/s, done.
From https://github.com/AristideI/Final-Git-Practice
   1731220..b3c85eb  main       -> origin/main
Updating 1731220..b3c85eb
Fast-forward
 README.md     | 60 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 services.html | 12 ++++++++++++
 2 files changed, 72 insertions(+)
 create mode 100644 README.md
 create mode 100644 services.html

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ git branch -d ft/service-redesign
Deleted branch ft/service-redesign (was 1731220).

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'

walte@Walter MINGW64 /d/Final-Git-Practice (ft/service-redesign)
$ ls
2  README.md  file  file2  fileone.html  services.html

walte@Walter MINGW64 /d/Final-Git-Practice (ft/service-redesign)
$ vi services.html

walte@Walter MINGW64 /d/Final-Git-Practice (ft/service-redesign)
$ add
[ft/service-redesign 090483c] Latest Update
 1 file changed, 6 insertions(+), 1 deletion(-)
fatal: The current branch ft/service-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/service-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


walte@Walter MINGW64 /d/Final-Git-Practice (ft/service-redesign)
$ git push origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 477 bytes | 477.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/AristideI/Final-Git-Practice/pull/new/ft/service-redesign
remote:
To https://github.com/AristideI/Final-Git-Practice.git
 * [new branch]      ft/service-redesign -> ft/service-redesign

walte@Walter MINGW64 /d/Final-Git-Practice (ft/service-redesign)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ vi services.html

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ add
[main e1fa1b8] Latest Update
 1 file changed, 4 insertions(+), 1 deletion(-)
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 484 bytes | 484.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/AristideI/Final-Git-Practice.git
   b3c85eb..e1fa1b8  main -> main

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ git diff ft/service-redesign
diff --git a/services.html b/services.html
index fa48e66..7a16b35 100644
--- a/services.html
+++ b/services.html
@@ -1,4 +1,7 @@
-- Commit the current changes and push them
+- Commit and push those changes
+- Now go back to the github PR you had created for the `ft/service-redesign`branch, you will then see that you have conflicts with the `main` branch
+- In your project checkout the `ft/service-redesign`branch
+- Compare the `ft/service-redesign`with the `main` branch using git diff and observe the changes- Commit the current changes and push them
 - Using stash pop restore the changes of the `team page` index
 - Reset the current changes using git reset and go back to the changes without the `team page`

@@ -9,9 +12,4 @@ Exercises 1
 - Create a new branch named `ft/bundle-2`
 - Add new changes to your project. create a new page named `services.html` and add some changes
 - Commit your changes and create a Pull Request against the `main` branch in your github repository
-- Request a review an- `ain` branch and pull the latest changes
-- Create a new branch named `ft/service-redesign`
-- Add new changes to the `service.html` page
-- commit and push them
-- create a new PR for your changes
-- go back to your `main` branch and add again new changes to your `service.html` page, you can add different changes but
+- Request a review an

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ git merge ft/service-redesign
Auto-merging services.html
Merge made by the 'ort' strategy.
 services.html | 7 ++++++-
 1 file changed, 6 insertions(+), 1 deletion(-)

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ add
On branch main
Your branch is ahead of 'origin/main' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ git push
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 521 bytes | 521.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/AristideI/Final-Git-Practice.git
   e1fa1b8..2c76058  main -> main

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$

```
