Daftar tugas / branch
1. Tugas-git
2. Tugas-html
3. Tugas-css
4. Tugas-js
5. Tugas-midProject
6. Tugas-php
7. Tugas-finalProject

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT (main)
$ git clone https://github.com/virnnp/belajarGIT
Cloning into 'belajarGIT'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
Receiving objects: 100% (6/6), done.

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT (main)
$ cd belajarGIT

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git checkout -b Tugas-git
Switched to a new branch 'Tugas-git'

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-git)
$ touch Tugas-Git.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-git)
$ git add Tugas-Git.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-git)
$ git commit -m "Menambahkan Tugas-Git.txt dengan isi bebas"
[Tugas-git dbb09ce] Menambahkan Tugas-Git.txt dengan isi bebas
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-git)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git merge Tugas-git
Updating bda92ad..dbb09ce
Fast-forward
 Tugas-Git.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Git.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 337 bytes | 337.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/virnnp/belajarGIT
   bda92ad..dbb09ce  main -> main

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git checkout -b Tugas-html
Switched to a new branch 'Tugas-html'

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-html)
$ touch Tugas-Html.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-html)
$ echo "teks file tugas-html" > Tugas-Html.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-html)
$ git add Tugas-Html.txt
warning: in the working copy of 'Tugas-Html.txt', LF will be replaced by CRLF the next time Git touches it

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-html)
$ git commit -m "Menambahkan Tugas-Html.txt dengan isi bebas"
[Tugas-html 6b0dd3f] Menambahkan Tugas-Html.txt dengan isi bebas
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-html)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git merge Tugas-html
Updating dbb09ce..6b0dd3f
Fast-forward
 Tugas-Html.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-Html.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 370 bytes | 123.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/virnnp/belajarGIT
   dbb09ce..6b0dd3f  main -> main

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git checkout -b Tugas-css
Switched to a new branch 'Tugas-css'

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-css)
$ echo "file teks tugas-css" > Tugas-css.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-css)
$ git add Tugas-css.txt
warning: in the working copy of 'Tugas-css.txt', LF will be replaced by CRLF the next time Git touches it

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-Html.txt dengan isi bebas"
[Tugas-css 2554562] Menambahkan Tugas-Html.txt dengan isi bebas
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-css.txt dengan isi bebas"
On branch Tugas-css
nothing to commit, working tree clean

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT
$ echo "Isi bebas file css" > Tugas-css.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-css)
$ git add Tugas-css.txt
warning: in the working copy of 'Tugas-css.txt', LF will be replaced by CRLF the next time Git touches it

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-css)
$ git commit -m "Menambahkan Tugas-css.txt dengan isi bebas"
[Tugas-css 489a7d9] Menambahkan Tugas-css.txt dengan isi bebas
 1 file changed, 1 insertion(+), 1 deletion(-)

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-css)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git merge Tugas-css
Updating 6b0dd3f..489a7d9
Fast-forward
 Tugas-css.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-css.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 592 bytes | 197.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
To https://github.com/virnnp/belajarGIT
   6b0dd3f..489a7d9  main -> main

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git checkout -b Tugas-js
Switched to a new branch 'Tugas-js'

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-js)
$ touch Tugas-js.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-js)
$ echo "Isi bebas file js" > Tugas-js.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-js)
$ git add Tugas-js.txt
warning: in the working copy of 'Tugas-js.txt', LF will be replaced by CRLF the next time Git touches it

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-js)
$ git commit -m "Menambahkan Tugas-js.txt dengan isi bebas"
[Tugas-js 97440d6] Menambahkan Tugas-js.txt dengan isi bebas
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-js)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git merge Tugas-js
Updating 489a7d9..97440d6
Fast-forward
 Tugas-js.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-js.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 330 bytes | 165.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/virnnp/belajarGIT
   489a7d9..97440d6  main -> main

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git checkout -b Tugas-^[[200~Tugas-html
fatal: 'Tugas-?[200~Tugas-html' is not a valid branch name

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git checkout -b Tugas-midProject
Switched to a new branch 'Tugas-midProject'

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-midProject)
$ touch Tugas-midProject.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-midProject)
$ echo "file UTS p.web" > Tugas-midProject.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject
fatal: pathspec 'Tugas-midProject' did not match any files

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-midProject)
$ git add Tugas-midProject.txt
warning: in the working copy of 'Tugas-midProject.txt', LF will be replaced by CRLF the next time Git touches it

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-midProject)
$ git commit -m "Menambahkan Tugas-midProject.txt dengan isi bebas"
[Tugas-midProject 128d63a] Menambahkan Tugas-midProject.txt dengan isi bebas
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-midProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git merge Tugas-midProject
Updating 97440d6..128d63a
Fast-forward
 Tugas-midProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-midProject.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 338 bytes | 338.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/virnnp/belajarGIT
   97440d6..128d63a  main -> main

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git checkout -b Tugas-php
Switched to a new branch 'Tugas-php'

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-php)
$ touch Tugas-php.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-php)
$ exho "tugas php file" > Tugas-php.txt
bash: exho: command not found

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-php)
$ echo "tugas php file" > Tugas-php.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-php)
$ git add Tugas-php.txt
warning: in the working copy of 'Tugas-php.txt', LF will be replaced by CRLF the next time Git touches it

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-php)
$ git commit -m "Menambahkan Tugas-php.txt dengan isi bebas"
[Tugas-php ce0c52b] Menambahkan Tugas-php.txt dengan isi bebas
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-php)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git merge Tugas-php
Updating 128d63a..ce0c52b
Fast-forward
 Tugas-php.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-php.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 326 bytes | 326.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/virnnp/belajarGIT
   128d63a..ce0c52b  main -> main

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git checkout -b Tugas-finalProject
Switched to a new branch 'Tugas-finalProject'

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-finalProject)
$ touch Tugas-finalProject.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-finalProject)
$ acho "tugas final project web programing" > Tugas-finalProject.txt
bash: acho: command not found

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-finalProject)
$ echo "tugas final project web programing" > Tugas-finalProject.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-finalProject)
$ git add Tugas-finalProject.txt
warning: in the working copy of 'Tugas-finalProject.txt', LF will be replaced by CRLF the next time Git touches it

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-finalProject)
$ git commit -m"Menambahkan Tugas-finalProject.txt dengan isi bebas"
[Tugas-finalProject 313ffd7] Menambahkan Tugas-finalProject.txt dengan isi bebas
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (Tugas-finalProject)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git merge Tugas-finalProject
Updating ce0c52b..313ffd7
Fast-forward
 Tugas-finalProject.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 Tugas-finalProject.txt

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 352 bytes | 352.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/virnnp/belajarGIT
   ce0c52b..313ffd7  main -> main
   

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git add README.md

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git commit -m "Menambahkan daftar perintah GiT"
[main 49dfd35] Menambahkan daftar perintah GiT
 1 file changed, 350 insertions(+)

ACER@LAPTOP-NALNC862 MINGW64 ~/belajarGIT/belajarGIT (main)
$ git push origin --all
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.87 KiB | 958.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/virnnp/belajarGIT
   313ffd7..49dfd35  main -> main
 * [new branch]      Tugas-css -> Tugas-css
 * [new branch]      Tugas-finalProject -> Tugas-finalProject
 * [new branch]      Tugas-git -> Tugas-git
 * [new branch]      Tugas-html -> Tugas-html
 * [new branch]      Tugas-js -> Tugas-js
 * [new branch]      Tugas-midProject -> Tugas-midProject
 * [new branch]      Tugas-php -> Tugas-php

