Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject
Daftar perintah GiT

adelc@ASUSVivobook MINGW64 /d/GIT/belajarGIT (main)
$ git branch Tugas-git

adelc@ASUSVivobook MINGW64 /d/GIT/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

adelc@ASUSVivobook MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Tugas-Git.txt

nothing added to commit but untracked files present (use "git add" to track)

adelc@ASUSVivobook MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

adelc@ASUSVivobook MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   Tugas-Git.txt


adelc@ASUSVivobook MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git commit
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'adelc@ASUSVivobook.(none)')

adelc@ASUSVivobook MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git config --global user.email "adelclangitan@gmail.com"

adelc@ASUSVivobook MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git config --global user.name "adelclra"

adelc@ASUSVivobook MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git commit -m "tugasgit"
[Tugas-git 19375ce] tugasgit
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-Git.txt

adelc@ASUSVivobook MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git status
On branch Tugas-git
nothing to commit, working tree clean

adelc@ASUSVivobook MINGW64 /d/GIT/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

adelc@ASUSVivobook MINGW64 /d/GIT/belajarGIT (main)
$ git merge Tugas-git
Updating 0e5e698..19375ce
Fast-forward
 Tugas-Git.txt | 2 ++
 1 file changed, 2 insertions(+)
 create mode 100644 Tugas-Git.txt

adelc@ASUSVivobook MINGW64 /d/GIT/belajarGIT (main)
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 316 bytes | 158.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/adelclra/belajarGIT.git
   0e5e698..19375ce  main -> main

