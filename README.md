\*\*Bundle 2 Execercise 1

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

\*\*Bundle 2 exercises 2

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

\*\* Bundle 3 Exercise 1
\*\*Cherry Pick

```

walte@Walter MINGW64 /d/Final-Git-Practice (ft/team-page)
$ vi team.html

walte@Walter MINGW64 /d/Final-Git-Practice (ft/team-page)
$ git add .
warning: in the working copy of 'team.html', LF will be replaced by CRLF the next time Git touches it

walte@Walter MINGW64 /d/Final-Git-Practice (ft/team-page)
$ git commit -m "team-page"
[ft/team-page e26f986] team-page
 1 file changed, 4 insertions(+)
 create mode 100644 team.html

walte@Walter MINGW64 /d/Final-Git-Practice (ft/team-page)
$ git push
fatal: The current branch ft/team-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/team-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


walte@Walter MINGW64 /d/Final-Git-Practice (ft/team-page)
$ git push origin ft/team-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 409 bytes | 409.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/AristideI/Final-Git-Practice/pull/new/ft/team-page
remote:
To https://github.com/AristideI/Final-Git-Practice.git
 * [new branch]      ft/team-page -> ft/team-page

walte@Walter MINGW64 /d/Final-Git-Practice (ft/team-page)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'

walte@Walter MINGW64 /d/Final-Git-Practice (ft/contact-page)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'

walte@Walter MINGW64 /d/Final-Git-Practice (ft/team-page)
$ git log
commit e26f986d8055916db641503d7f7eeb924d0ebead (HEAD -> ft/team-page, origin/ft/team-page)
Author: AristideI <a.isingizwe@alustudent.com>
Date:   Wed Jul 26 11:13:46 2023 +0200

    team-page

commit 8f9760a1f0a93de1156290765885509ab7367a87 (origin/main, main, ft/contact-page)
Author: AristideI <a.isingizwe@alustudent.com>
Date:   Wed Jul 26 11:06:13 2023 +0200

    Latest Update

commit 2c76058b5c4f7500c8eb064e7b6355b0cdf0393d
Merge: e1fa1b8 090483c
Author: AristideI <a.isingizwe@alustudent.com>
Date:   Wed Jul 26 11:04:22 2023 +0200

    Merge branch 'ft/service-redesign'

commit e1fa1b89fd0f50629de4eaa308f06527890890de
Author: AristideI <a.isingizwe@alustudent.com>
Date:   Wed Jul 26 11:03:05 2023 +0200

    Latest Update

commit 090483c7a19952456aa12c38d177739e541bbecd (origin/ft/service-redesign, ft/service-redesign)
Author: AristideI <a.isingizwe@alustudent.com>
Date:   Wed Jul 26 11:00:27 2023 +0200

    Latest Update

commit b3c85eb1c556e2a14884bfc1cb502415ca9f0727
Merge: 1731220 6754d09
Author: AristideI <115247039+AristideI@users.noreply.github.com>
Date:   Wed Jul 26 10:57:03 2023 +0200

    Merge pull request #2 from AristideI/ft/bundle-2

    Ft/bundle 2

commit 6754d097f0c9c8963e7424eac011bb7c690ba7ea (origin/ft/bundle-2, ft/bundle-2)
Author: AristideI <a.isingizwe@alustudent.com>
Date:   Wed Jul 26 10:54:54 2023 +0200

    Latest Update

commit db2bbce4b629007a61173ec0f7fda91e5cb779e4

walte@Walter MINGW64 /d/Final-Git-Practice (ft/team-page)
$ git che
checkout      cherry        cherry-pick

walte@Walter MINGW64 /d/Final-Git-Practice (ft/team-page)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'

walte@Walter MINGW64 /d/Final-Git-Practice (ft/contact-page)
$ git cherry-pick e26f986d8055916db641503d7f7eeb924d0ebead
[ft/contact-page 5a1e212] team-page
 Date: Wed Jul 26 11:13:46 2023 +0200
 1 file changed, 4 insertions(+)
 create mode 100644 team.html

walte@Walter MINGW64 /d/Final-Git-Practice (ft/contact-page)
$ git add .

walte@Walter MINGW64 /d/Final-Git-Practice (ft/contact-page)
$ git commit - "cheerry pick"
error: pathspec '-' did not match any file(s) known to git
error: pathspec 'cheerry pick' did not match any file(s) known to git

walte@Walter MINGW64 /d/Final-Git-Practice (ft/contact-page)
$ git push origin ft/contact-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 415 bytes | 415.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/AristideI/Final-Git-Practice/pull/new/ft/contact-page
remote:
To https://github.com/AristideI/Final-Git-Practice.git
 * [new branch]      ft/contact-page -> ft/contact-page

walte@Walter MINGW64 /d/Final-Git-Practice (ft/contact-page)
$

```

\*\* FAQ page

```

walte@Walter MINGW64 /d/Final-Git-Practice (ft/team-page)
$ vi team.html

walte@Walter MINGW64 /d/Final-Git-Practice (ft/team-page)
$ git add .
warning: in the working copy of 'team.html', LF will be replaced by CRLF the next time Git touches it

walte@Walter MINGW64 /d/Final-Git-Practice (ft/team-page)
$ git commit -m "team-page"
[ft/team-page e26f986] team-page
 1 file changed, 4 insertions(+)
 create mode 100644 team.html

walte@Walter MINGW64 /d/Final-Git-Practice (ft/team-page)
$ git push
fatal: The current branch ft/team-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/team-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


walte@Walter MINGW64 /d/Final-Git-Practice (ft/team-page)
$ git push origin ft/team-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 409 bytes | 409.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/AristideI/Final-Git-Practice/pull/new/ft/team-page
remote:
To https://github.com/AristideI/Final-Git-Practice.git
 * [new branch]      ft/team-page -> ft/team-page

walte@Walter MINGW64 /d/Final-Git-Practice (ft/team-page)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'

walte@Walter MINGW64 /d/Final-Git-Practice (ft/contact-page)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'

walte@Walter MINGW64 /d/Final-Git-Practice (ft/team-page)
$ git log
commit e26f986d8055916db641503d7f7eeb924d0ebead (HEAD -> ft/team-page, origin/ft/team-page)
Author: AristideI <a.isingizwe@alustudent.com>
Date:   Wed Jul 26 11:13:46 2023 +0200

    team-page

commit 8f9760a1f0a93de1156290765885509ab7367a87 (origin/main, main, ft/contact-page)
Author: AristideI <a.isingizwe@alustudent.com>
Date:   Wed Jul 26 11:06:13 2023 +0200

    Latest Update

commit 2c76058b5c4f7500c8eb064e7b6355b0cdf0393d
Merge: e1fa1b8 090483c
Author: AristideI <a.isingizwe@alustudent.com>
Date:   Wed Jul 26 11:04:22 2023 +0200

    Merge branch 'ft/service-redesign'

commit e1fa1b89fd0f50629de4eaa308f06527890890de
Author: AristideI <a.isingizwe@alustudent.com>
Date:   Wed Jul 26 11:03:05 2023 +0200

    Latest Update

commit 090483c7a19952456aa12c38d177739e541bbecd (origin/ft/service-redesign, ft/service-redesign)
Author: AristideI <a.isingizwe@alustudent.com>
Date:   Wed Jul 26 11:00:27 2023 +0200

    Latest Update

commit b3c85eb1c556e2a14884bfc1cb502415ca9f0727
Merge: 1731220 6754d09
Author: AristideI <115247039+AristideI@users.noreply.github.com>
Date:   Wed Jul 26 10:57:03 2023 +0200

    Merge pull request #2 from AristideI/ft/bundle-2

    Ft/bundle 2

commit 6754d097f0c9c8963e7424eac011bb7c690ba7ea (origin/ft/bundle-2, ft/bundle-2)
Author: AristideI <a.isingizwe@alustudent.com>
Date:   Wed Jul 26 10:54:54 2023 +0200

    Latest Update

commit db2bbce4b629007a61173ec0f7fda91e5cb779e4

walte@Walter MINGW64 /d/Final-Git-Practice (ft/team-page)
$ git che
checkout      cherry        cherry-pick

walte@Walter MINGW64 /d/Final-Git-Practice (ft/team-page)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'

walte@Walter MINGW64 /d/Final-Git-Practice (ft/contact-page)
$ git cherry-pick e26f986d8055916db641503d7f7eeb924d0ebead
[ft/contact-page 5a1e212] team-page
 Date: Wed Jul 26 11:13:46 2023 +0200
 1 file changed, 4 insertions(+)
 create mode 100644 team.html

walte@Walter MINGW64 /d/Final-Git-Practice (ft/contact-page)
$ git add .

walte@Walter MINGW64 /d/Final-Git-Practice (ft/contact-page)
$ git commit - "cheerry pick"
error: pathspec '-' did not match any file(s) known to git
error: pathspec 'cheerry pick' did not match any file(s) known to git

walte@Walter MINGW64 /d/Final-Git-Practice (ft/contact-page)
$ git push origin ft/contact-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 415 bytes | 415.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/AristideI/Final-Git-Practice/pull/new/ft/contact-page
remote:
To https://github.com/AristideI/Final-Git-Practice.git
 * [new branch]      ft/contact-page -> ft/contact-page

walte@Walter MINGW64 /d/Final-Git-Practice (ft/contact-page)
$ vi README.md

walte@Walter MINGW64 /d/Final-Git-Practice (ft/contact-page)
$ git add .

walte@Walter MINGW64 /d/Final-Git-Practice (ft/contact-page)
$ git commit -m sdf
[ft/contact-page 350f2d5] sdf
 1 file changed, 151 insertions(+)

walte@Walter MINGW64 /d/Final-Git-Practice (ft/contact-page)
$ git push origin ft/contact-page
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.30 KiB | 1.30 MiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/AristideI/Final-Git-Practice.git
   5a1e212..350f2d5  ft/contact-page -> ft/contact-page

walte@Walter MINGW64 /d/Final-Git-Practice (ft/contact-page)
$ git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'

walte@Walter MINGW64 /d/Final-Git-Practice (ft/faq-page)
$ vi faq.html

walte@Walter MINGW64 /d/Final-Git-Practice (ft/faq-page)
$ add
warning: in the working copy of 'faq.html', LF will be replaced by CRLF the next time Git touches it
[ft/faq-page 79dd6ca] Latest Update
 1 file changed, 9 insertions(+)
 create mode 100644 faq.html
fatal: The current branch ft/faq-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/faq-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


walte@Walter MINGW64 /d/Final-Git-Practice (ft/faq-page)
$ git push origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 503 bytes | 503.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/AristideI/Final-Git-Practice/pull/new/ft/faq-page
remote:
To https://github.com/AristideI/Final-Git-Practice.git
 * [new branch]      ft/faq-page -> ft/faq-page

walte@Walter MINGW64 /d/Final-Git-Practice (ft/faq-page)
$ git revert e26f986d8055916db641503d7f7eeb924d0ebead
[ft/faq-page a5f17ff] Revert "team-page"
 1 file changed, 4 deletions(-)
 delete mode 100644 team.html

walte@Walter MINGW64 /d/Final-Git-Practice (ft/faq-page)
$ git add .

walte@Walter MINGW64 /d/Final-Git-Practice (ft/faq-page)
$ git commit -m "the"
On branch ft/faq-page
nothing to commit, working tree clean

walte@Walter MINGW64 /d/Final-Git-Practice (ft/faq-page)
$ git push
fatal: The current branch ft/faq-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/faq-page

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


walte@Walter MINGW64 /d/Final-Git-Practice (ft/faq-page)
$ git push origin ft/faq-page
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 274 bytes | 274.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/AristideI/Final-Git-Practice.git
   79dd6ca..a5f17ff  ft/faq-page -> ft/faq-page

walte@Walter MINGW64 /d/Final-Git-Practice (ft/faq-page)
$


```
