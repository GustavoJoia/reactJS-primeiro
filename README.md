Aluno@PC101 MINGW64 ~/Desktop/projetoExpo
$ git init
Initialized empty Git repository in C:/Users/Aluno/Desktop/projetoExpo/.git/

Aluno@PC101 MINGW64 ~/Desktop/projetoExpo (master)
$ git add .
warning: LF will be replaced by CRLF in .expo-shared/assets.json.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in .gitignore.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in App.js.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in app.json.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in babel.config.js.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in package.json.
The file will have its original line endings in your working directory

Aluno@PC101 MINGW64 ~/Desktop/projetoExpo (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   .expo-shared/assets.json
        new file:   .gitignore
        new file:   App.js
        new file:   app.json
        new file:   assets/adaptive-icon.png
        new file:   assets/favicon.png
        new file:   assets/icon.png
        new file:   assets/splash.png
        new file:   babel.config.js
        new file:   package.json
        new file:   yarn.lock


Aluno@PC101 MINGW64 ~/Desktop/projetoExpo (master)
$ git commit -m "14/02 - Primeira Versão Projeto (React Native)"
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Aluno@PC101.(none)')

Aluno@PC101 MINGW64 ~/Desktop/projetoExpo (master)
$ git config --global user.email "gustavo.joia57@gmail.com"

Aluno@PC101 MINGW64 ~/Desktop/projetoExpo (master)
$ git commit -m "14/02 - Primeira Versão Projeto (React Native)"
[master (root-commit) 3532f1c] 14/02 - Primeira Versão Projeto (React Native)
 11 files changed, 5574 insertions(+)
 create mode 100644 .expo-shared/assets.json
 create mode 100644 .gitignore
 create mode 100644 App.js
 create mode 100644 app.json
 create mode 100644 assets/adaptive-icon.png
 create mode 100644 assets/favicon.png
 create mode 100644 assets/icon.png
 create mode 100644 assets/splash.png
 create mode 100644 babel.config.js
 create mode 100644 package.json
 create mode 100644 yarn.lock

Aluno@PC101 MINGW64 ~/Desktop/projetoExpo (master)
$ git remote add origin https://github.com/GustavoJoia/reactJS-primeiro.git

Aluno@PC101 MINGW64 ~/Desktop/projetoExpo (master)
$ git push -u origin master
Enumerating objects: 15, done.
Counting objects: 100% (15/15), done.
Delta compression using up to 12 threads
Compressing objects: 100% (14/14), done.
Writing objects: 100% (15/15), 163.41 KiB | 14.85 MiB/s, done.
Total 15 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/GustavoJoia/reactJS-primeiro.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

Aluno@PC101 MINGW64 ~/Desktop/projetoExpo (master)
$ git add .
warning: LF will be replaced by CRLF in App.js.
The file will have its original line endings in your working directory

Aluno@PC101 MINGW64 ~/Desktop/projetoExpo (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   App.js


Aluno@PC101 MINGW64 ~/Desktop/projetoExpo (master)
$ git commit -m "Adição de textos-teste e botões"
[master 36bce9e] Adição de textos-teste e botões
 1 file changed, 3 insertions(+)

Aluno@PC101 MINGW64 ~/Desktop/projetoExpo (master)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 369 bytes | 369.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/GustavoJoia/reactJS-primeiro.git
   3532f1c..36bce9e  master -> master

Aluno@PC101 MINGW64 ~/Desktop/projetoExpo (master)
$
