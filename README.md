
```

walte@Walter MINGW64 /d
$ cd Final-Git-Practice/

walte@Walter MINGW64 /d/Final-Git-Practice
$ git init
Initialized empty Git repository in D:/Final-Git-Practice/.git/

walte@Walter MINGW64 /d/Final-Git-Practice (master)
$ git branch -m master main

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ vi fileone.html

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ git add .
warning: in the working copy of 'fileone.html', LF will be replaced by CRLF the next time Git touches it

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ git commit -m "initialising"
[main (root-commit) 9a4ace5] initialising
 1 file changed, 9 insertions(+)
 create mode 100644 fileone.html

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ git remote add https://github.com/AristideI/Final-Git-Practice.git
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from


walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ git remote add origin https://github.com/AristideI/Final-Git-Practice.git

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ add
On branch main
nothing to commit, working tree clean

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ git add .

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ git commit -m "init"
On branch main
nothing to commit, working tree clean

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 437 bytes | 437.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/AristideI/Final-Git-Practice.git
 * [new branch]      main -> main

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ touch file 2

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ add
[main 3422c18] Latest Update
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 2
 create mode 100644 file
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ git push --set-upstream origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 283 bytes | 283.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/AristideI/Final-Git-Practice.git
   9a4ace5..3422c18  main -> main
branch 'main' set up to track 'origin/main'.

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ touch file2

walte@Walter MINGW64 /d/Final-Git-Practice (main)
$ add
[main 1731220] Latest Update
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 file2
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 232 bytes | 232.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/AristideI/Final-Git-Practice.git
   3422c18..1731220  main -> main


```

** Exercise 2


```
$ git checkout -b dev
Switched to a new branch 'dev'

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ git checkout -b test
Switched to a new branch 'test'

walte@Walter MINGW64 /d/Final-Git-Practice (test)
$ git checkout dev
Switched to branch 'dev'

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ git branch -d test
Deleted branch test (was 1731220).

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ aff
bash: aff: command not found

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ add
warning: in the working copy of 'README.md', LF will be replaced by CRLF the next time Git touches it
[dev 4b2a371] Latest Update
 1 file changed, 128 insertions(+)
 create mode 100644 README.md
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ nf home.html

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ git stach
git: 'stach' is not a git command. See 'git --help'.

The most similar command is
        stash

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ git stash
No local changes to save

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ ls
2  README.md  file  file2  fileone.html  home.html*

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ vi home.html

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ git stach push one
git: 'stach' is not a git command. See 'git --help'.

The most similar command is
        stash

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ git stash push one
error: pathspec ':(,prefix:0)one' did not match any file(s) known to git
Did you forget to 'git add'?

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ git stash push -m one
No local changes to save

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ add
warning: in the working copy of 'home.html', LF will be replaced by CRLF the next time Git touches it
[dev c9d593a] Latest Update
 1 file changed, 127 insertions(+)
 create mode 100644 home.html
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ vi home.html

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ git stach push -m "one"
git: 'stach' is not a git command. See 'git --help'.

The most similar command is
        stash

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ git stash push -m "one"
warning: in the working copy of 'home.html', LF will be replaced by CRLF the next time Git touches it
Saved working directory and index state On dev: one

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ vi about.html

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ add
warning: in the working copy of 'about.html', LF will be replaced by CRLF the next time Git touches it
[dev 5171965] Latest Update
 1 file changed, 1 insertion(+)
 create mode 100644 about.html
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ git stash list
stash@{0}: On dev: one

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ vi about.html

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ git stash push -m "two"
warning: in the working copy of 'about.html', LF will be replaced by CRLF the next time Git touches it
Saved working directory and index state On dev: two

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ vi team.html

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ add
warning: in the working copy of 'team.html', LF will be replaced by CRLF the next time Git touches it
[dev cc4b3eb] Latest Update
 1 file changed, 9 insertions(+)
 create mode 100644 team.html
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ vi team.html

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ git stash push -m "three"
warning: in the working copy of 'team.html', LF will be replaced by CRLF the next time Git touches it
Saved working directory and index state On dev: three

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ git stash list
stash@{0}: On dev: three
stash@{1}: On dev: two
stash@{2}: On dev: one

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ git stash pop 1
On branch dev
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   about.html

no changes added to commit (use "git add" and/or "git commit -a")
Dropped refs/stash@{1} (2b0a60894192affb1764319d477c1d6dc2688771)

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ git stash pop 1
On branch dev
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   about.html
        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")
Dropped refs/stash@{1} (a618e9e34073ff39223f4371ca29a09a5521c353)

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ add
[dev d7657c0] Latest Update
 2 files changed, 132 insertions(+), 1 deletion(-)
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ git push origin dev
Enumerating objects: 17, done.
Counting objects: 100% (17/17), done.
Delta compression using up to 12 threads
Compressing objects: 100% (15/15), done.
Writing objects: 100% (16/16), 2.60 KiB | 2.60 MiB/s, done.
Total 16 (delta 7), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (7/7), done.
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/AristideI/Final-Git-Practice/pull/new/dev
remote:
To https://github.com/AristideI/Final-Git-Practice.git
 * [new branch]      dev -> dev

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ git log
commit d7657c0735be976c9f093ab863496e6eb2a55e30 (HEAD -> dev, origin/dev)
Author: AristideI <a.isingizwe@alustudent.com>
Date:   Tue Jul 25 10:59:40 2023 +0200

    Latest Update

commit cc4b3eb2e91ebdfbbe8f1fad29c4a7f2103f091a
Author: AristideI <a.isingizwe@alustudent.com>
Date:   Tue Jul 25 10:58:37 2023 +0200

    Latest Update

commit 51719652c15390676dbe614bb5d113bb37e1dab5
Author: AristideI <a.isingizwe@alustudent.com>
Date:   Tue Jul 25 10:57:33 2023 +0200

    Latest Update

commit c9d593acd685d3d1f81d139964ab96fc4b14e7eb
Author: AristideI <a.isingizwe@alustudent.com>
Date:   Tue Jul 25 10:54:16 2023 +0200

    Latest Update

commit 4b2a371c7da7029e41b2966df30b989bf89d8a0a
Author: AristideI <a.isingizwe@alustudent.com>
Date:   Tue Jul 25 10:44:20 2023 +0200

    Latest Update

commit 173122046e3b69586aef6b4b1b1b6730f75d0663 (origin/main, main)
Author: AristideI <a.isingizwe@alustudent.com>
Date:   Tue Jul 25 10:27:44 2023 +0200

    Latest Update

commit 3422c18f9cefe20683462c8e4af614fc9815be8e
Author: AristideI <a.isingizwe@alustudent.com>
Date:   Tue Jul 25 10:26:34 2023 +0200

    Latest Update

commit 9a4ace59463d2033ffec39dde36d1e5b80dd064a
Author: AristideI <a.isingizwe@alustudent.com>
Date:   Tue Jul 25 10:22:46 2023 +0200

    initialising

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ git reset --soft  4b2a371c7da7029e41b2966df30b989bf89d8a0a

walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ add
[dev 870a267] Latest Update
 3 files changed, 268 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html
 create mode 100644 team.html
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


walte@Walter MINGW64 /d/Final-Git-Practice (dev)
$ vi README.md

walte@Walter MINGW64 /d/Final-Git-Practice (dev)


```
