# belajarGIT

Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject

Daftar perintah GIT
....

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop (main)
$ git config --global user.email "salibanasabdawita@gmail.com"

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop (main)
$ git init
Initialized empty Git repository in C:/Users/SABDA/Desktop/.git/

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop (main)
$ cd Desktop
bash: cd: Desktop: No such file or directory

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop (main)
$ git clone https://github.com/witaa07/belajarGIT.git
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop (main)
$ cd belajarGIT

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git branch
* main

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git branch Tugas-git

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git branch
  Tugas-git
* main

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git checkout Tugas-git
Switched to branch 'Tugas-git'

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-git)
$ touch Tugas-git.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan file Tugas-git.txt"
[Tugas-git 6244406] Menambahkan file Tugas-git.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-git.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-git)
$ git add Tugas-git.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan perubahan pada Tugas-git.txt"
[Tugas-git 6ecb55f] Menambahkan perubahan pada Tugas-git.txt
 1 file changed, 1 insertion(+)

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git merge Tugas-git
Updating 0cc93ae..6ecb55f
Fast-forward
 Tugas-git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-git.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 576 bytes | 288.00 KiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/witaa07/belajarGIT.git
   0cc93ae..6ecb55f  main -> main

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ cd belajarGIT
bash: cd: belajarGIT: No such file or directory

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git branch
  Tugas-git
* main

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git branch Tugas-html

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git branch
  Tugas-git
  Tugas-html
* main

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git checkout Tugas-html
Switched to branch 'Tugas-html'

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-html)
$ touch Tugas-html.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan file Tugas-html.txt"
[Tugas-html 7534e6d] Menambahkan file Tugas-html.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-html.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-html)
$ git add Tugas-html.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan perubahan pada Tugas-html.txt"
[Tugas-html aeff1b9] Menambahkan perubahan pada Tugas-html.txt
 1 file changed, 1 insertion(+)

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git merge Tugas-html
Updating 6ecb55f..aeff1b9
Fast-forward
 Tugas-html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-html.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 567 bytes | 283.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/witaa07/belajarGIT.git
   6ecb55f..aeff1b9  main -> main

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ cd belajarGIT
bash: cd: belajarGIT: No such file or directory

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git branch
  Tugas-git
  Tugas-html
* main

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git branch Tugas-css

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
* main

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git checkout Tugas-css
Switched to branch 'Tugas-css'

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-css)
$ touch Tugas-css.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan file Tugas-css.txt"
[Tugas-css f9471dc] Menambahkan file Tugas-css.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-css.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-css)
$ git add Tugas-css.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan perubahan pada Tugas-css.txt"
[Tugas-css fc263d4] Menambahkan perubahan pada Tugas-css.txt
 1 file changed, 1 insertion(+)

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git merge Tugas-css
Updating aeff1b9..fc263d4
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 596 bytes | 298.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/witaa07/belajarGIT.git
   aeff1b9..fc263d4  main -> main

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ cd belajarGIT
bash: cd: belajarGIT: No such file or directory

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
* main

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git branch Tugas-js

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
* main

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git checkout Tugas-js
Switched to branch 'Tugas-js'

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan file Tugas-js.txt"
[Tugas-js 2ae453d] Menambahkan file Tugas-js.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-js.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-js)
$ git add Tugas-js.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan perubahan pada Tugas-js.txt"
[Tugas-js bd085a4] Menambahkan perubahan pada Tugas-js.txt
 1 file changed, 1 insertion(+)

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git merge Tugas-js
Updating fc263d4..bd085a4
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 527 bytes | 263.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/witaa07/belajarGIT.git
   fc263d4..bd085a4  main -> main

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ cd belajarGIT
bash: cd: belajarGIT: No such file or directory

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
* main

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git branch Tugas-midProject

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
* main

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git checkout Tugas-midProject
Switched to branch 'Tugas-midProject'

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan file Tugas-midProject.txt"
[Tugas-midProject 9fc608d] Menambahkan file Tugas-midProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-midProject.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan perubahan pada Tugas-midProject.txt"
[Tugas-midProject 0f3f663] Menambahkan perubahan pada Tugas-midProject.txt
 1 file changed, 1 insertion(+)

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git merge Tugas-midProject
Updating bd085a4..0f3f663
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 555 bytes | 277.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/witaa07/belajarGIT.git
   bd085a4..0f3f663  main -> main

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ cd belajarGIT
bash: cd: belajarGIT: No such file or directory

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
* main

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git branch Tugas-php

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git checkout Tugas-php
Switched to branch 'Tugas-php'

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan file Tugas-php.txt"
[Tugas-php 8bd7af2] Menambahkan file Tugas-php.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-php.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan perubahan pada Tugas-php.txt"
[Tugas-php 5dee7e3] Menambahkan perubahan pada Tugas-php.txt
 1 file changed, 1 insertion(+)

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-php)
$ git checkout main
error: Your local changes to the following files would be overwritten by checkout:
        Tugas-php.txt
Please commit your changes or stash them before you switch branches.
Aborting

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-php)
$ git add Tugas-php.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan perubahan pada Tugas-php.txt"
[Tugas-php 7465647] Menambahkan perubahan pada Tugas-php.txt
 1 file changed, 1 insertion(+), 1 deletion(-)

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git merge Tugas-php
Updating 0f3f663..7465647
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git push origin main
Enumerating objects: 10, done.
Counting objects: 100% (10/10), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (9/9), 763 bytes | 254.00 KiB/s, done.
Total 9 (delta 3), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (3/3), completed with 1 local object.
To https://github.com/witaa07/belajarGIT.git
   0f3f663..7465647  main -> main

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ cd belajarGIT
bash: cd: belajarGIT: No such file or directory

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git branch Tugas-finalProject

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git branch
  Tugas-css
  Tugas-finalProject
  Tugas-git
  Tugas-html
  Tugas-js
  Tugas-midProject
  Tugas-php
* main

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git checkout Tugas-finalProject
Switched to branch 'Tugas-finalProject'

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan file Tugas-finalProject.txt"
[Tugas-finalProject b306b4b] Menambahkan file Tugas-finalProject.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Tugas-finalProject.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-finalProject)
$ git commit -m "Menambahkan perubahan pada Tugas-finalProject.txt"
[Tugas-finalProject 7508230] Menambahkan perubahan pada Tugas-finalProject.txt
 1 file changed, 1 insertion(+)

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git merge Tugas-finalproject
Updating 7465647..7508230
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 555 bytes | 277.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/witaa07/belajarGIT.git
   7465647..7508230  main -> main

SABDA@DESKTOP-11NOSH2 MINGW64 ~/Desktop/belajarGIT (main)
$
