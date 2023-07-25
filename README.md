
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
