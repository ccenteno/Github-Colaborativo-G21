# Github Colaborativo G21

```
git init
git status
git add index.html
git add .
git add -A
git commit -m "mi mensaje"
git log

git branch -M main
```

```
#…o crear un nuevo repositorio en la línea de comandos
echo "# Github-Colaborativo-G21" >> README.md 
git init 
git add README.md 
git commit -m "primer commit" 
git branch -M main 
git remote add origin https://github.com/ccenteno/Github-Colaborativo-G21.git
 git push -u origin main
#…o enviar un repositorio existente desde la línea de comandos
git remoto agregar origen https://github.com/ccenteno/Github-Colaborativo-G21.git
 git branch -M main 
git push -u origin main

git push origin main
git push
```
```
git swith -c Cesar
git branch

git switch main
git checkout main

git checkout Cesar
git switch Cesar
```

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21
$ git init
Initialized empty Git repository in C:/Github-Colaborativo-G21/.git/

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.html
        style.css

nothing added to commit but untracked files present (use "git add" to track)

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git add index.html

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git status                                                                                                                                                                                                                      
On branch master        

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        style.css


CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git commit -m "Agregando archivo index.html con la estructura html base"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'CCenteno@DESKTOP-R47N9N7.(none)')

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git config
error: no action specified

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git config --global user.email "ccentenor@gmail.com"

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git config --global user.name "César A. Centeno"

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git commit -m "Agregando archivo index.html con la estructura html base"
[master (root-commit) 339474c] Agregando archivo index.html con la estructura html base
 1 file changed, 11 insertions(+)
 create mode 100644 index.html

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        style.css

nothing added to commit but untracked files present (use "git add" to track)

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git log
commit 339474cb5da0a97cb6a186b480b68a5b6ef34b40 (HEAD -> master)
Author: César A. Centeno <ccentenor@gmail.com>
Date:   Thu Sep 5 19:30:01 2024 -0500

    Agregando archivo index.html con la estructura html base

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git add styles.css
fatal: pathspec 'styles.css' did not match any files

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git commit -m "Agregando archivo styles.css"
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        style.css

nothing added to commit but untracked files present (use "git add" to track)

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git log
commit 339474cb5da0a97cb6a186b480b68a5b6ef34b40 (HEAD -> master)
Author: César A. Centeno <ccentenor@gmail.com>
Date:   Thu Sep 5 19:30:01 2024 -0500

    Agregando archivo index.html con la estructura html base

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        style.css

nothing added to commit but untracked files present (use "git add" to track)

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git add style.css

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git commit -m "Agregando archivo style.css"
[master 0e28473] Agregando archivo style.css
 1 file changed, 3 insertions(+)
 create mode 100644 style.css

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git log
commit 0e284739681ad92492a8a65ff5b51540525189b0 (HEAD -> master)
Author: César A. Centeno <ccentenor@gmail.com>
Date:   Thu Sep 5 19:34:20 2024 -0500

    Agregando archivo style.css

commit 339474cb5da0a97cb6a186b480b68a5b6ef34b40
Author: César A. Centeno <ccentenor@gmail.com>
Date:   Thu Sep 5 19:30:01 2024 -0500

    Agregando archivo index.html con la estructura html base

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git restore index.html

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git status
On branch master
nothing to commit, working tree clean

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git log
commit 0e284739681ad92492a8a65ff5b51540525189b0 (HEAD -> master)
Author: César A. Centeno <ccentenor@gmail.com>
Date:   Thu Sep 5 19:34:20 2024 -0500

    Agregando archivo style.css

commit 339474cb5da0a97cb6a186b480b68a5b6ef34b40
Author: César A. Centeno <ccentenor@gmail.com>
Date:   Thu Sep 5 19:30:01 2024 -0500

    Agregando archivo index.html con la estructura html base

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git add README.md

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   README.md


CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git commit -m "Agregando archivo README.md"
[master d2633d2] Agregando archivo README.md
 1 file changed, 194 insertions(+)
 create mode 100644 README.md

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (master)
$ git branch -M main

CCenteno@DESKTOP-R47N9N7 MINGW64 /c/Github-Colaborativo-G21 (main)
$


formato .md (mark down)