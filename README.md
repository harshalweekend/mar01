# mar01
mar01
this is branch 2 
this is data.

Shree@DESKTOP-UJ36G3U MINGW64 /c/GITH01
$ git push origin HEAD
fatal: not a git repository (or any of the parent directories): .git

Shree@DESKTOP-UJ36G3U MINGW64 /c/GITH01
$ cd mar01/

Shree@DESKTOP-UJ36G3U MINGW64 /c/GITH01/mar01 (b01)
$ cd mar01/
bash: cd: mar01/: No such file or directory

Shree@DESKTOP-UJ36G3U MINGW64 /c/GITH01/mar01 (b01)
$ git push origin HEAD


Shree@DESKTOP-UJ36G3U MINGW64 /c/GITH01/mar01 (b01)
$ git push origin HEAD
Everything up-to-date

Shree@DESKTOP-UJ36G3U MINGW64 /c/GITH01/mar01 (b01)
$ ^C

Shree@DESKTOP-UJ36G3U MINGW64 /c/GITH01/mar01 (b02)
$ git push origin b02 


Shree@DESKTOP-UJ36G3U MINGW64 /c/GITH01/mar01 (b02)
$ git push origin b02 


Shree@DESKTOP-UJ36G3U MINGW64 /c/GITH01/mar01 (b02)
$ git push origin b02 
fatal: A task was canceled.
Everything up-to-date

Shree@DESKTOP-UJ36G3U MINGW64 /c/GITH01/mar01 (b02)
$ git branch 
  b01
* b02
  main

Shree@DESKTOP-UJ36G3U MINGW64 /c/GITH01/mar01 (b02)
$ git pull origin bo01
fatal: couldn't find remote ref bo01

Shree@DESKTOP-UJ36G3U MINGW64 /c/GITH01/mar01 (b02)
$ git pull origin b01
From https://github.com/harshalweekend/mar01
 * branch            b01        -> FETCH_HEAD
Auto-merging README.md
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.

Shree@DESKTOP-UJ36G3U MINGW64 /c/GITH01/mar01 (b02|MERGING)
$ git status 
On branch b02
Your branch is up to date with 'origin/b02'.

You have unmerged paths.
  (fix conflicts and run "git commit")
  (use "git merge --abort" to abort the merge)

Unmerged paths:
  (use "git add <file>..." to mark resolution)
        both modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

Shree@DESKTOP-UJ36G3U MINGW64 /c/GITH01/mar01 (b02|MERGING)
$ gir add .
bash: gir: command not found

Shree@DESKTOP-UJ36G3U MINGW64 /c/GITH01/mar01 (b02|MERGING)
$ gig add .
bash: gig: command not found

Shree@DESKTOP-UJ36G3U MINGW64 /c/GITH01/mar01 (b02|MERGING)
$ git add .

Shree@DESKTOP-UJ36G3U MINGW64 /c/GITH01/mar01 (b02|MERGING)
$ git commit -m "this is marge op"
[b02 bfc6137] this is marge op

Shree@DESKTOP-UJ36G3U MINGW64 /c/GITH01/mar01 (b02)
$ git push origin b02
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Writing objects: 100% (3/3), 307 bytes | 307.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/harshalweekend/mar01.git
   e0f5008..bfc6137  b02 -> b02

Shree@DESKTOP-UJ36G3U MINGW64 /c/GITH01/mar01 (b02)
$ git commit -m "this is marge op"

