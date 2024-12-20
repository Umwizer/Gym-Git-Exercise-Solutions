# Gym-Git-Exercise-Solutions
## Bundle 1
### Exercise 1
UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github

$ `git branch master` 
fatal: not a git repository (or any of the parent directories): .git

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github
$  cd Gym-Git-Exercise-Solutions/

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (main)
$ `git branch master`

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (main)
$ `git checkout master`
Switched to branch 'master'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (master)
$ `git add .`

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (master)
$ `git commit -m "changing main to master` "
[master ba76c20] changing main to master
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.html

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (master)
$` git push origin master`
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 285 bytes | 142.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: 
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/Umwizer/Gym-Git-Exercise-Solutions/pull/new/master
remote:
To https://github.com/Umwizer/Gym-Git-Exercise-Solutions.git
 * [new branch]      master -> master

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (master)
$ `git branch dev`

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (master)
$ `git checkout dev`
Switched to branch 'dev'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ `git branch test`

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ `git checkout test`
Switched to branch 'test'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (test)
$ `git checkout dev`
Switched to branch 'dev'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ `git branch -d test`
Deleted branch test (was ba76c20).

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github
$ git branch master 
fatal: not a git repository (or any of the parent directories): .git

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github
$ cd Gym-Git-Exercise-Solutions/

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (main)
$ git branch master

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (main)
$ git checkout master
Switched to branch 'master'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (master)
$ git add .

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (master)
$ git commit -m "changing main to master "
[master ba76c20] changing main to master
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.html

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (master)
$ git push origin master
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 285 bytes | 142.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: 
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/Umwizer/Gym-Git-Exercise-Solutions/pull/new/master
remote:
To https://github.com/Umwizer/Gym-Git-Exercise-Solutions.git
 * [new branch]      master -> master

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (master)
$ git branch dev

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (master)
$ git checkout dev
Switched to branch 'dev'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ git branch test

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ git checkout test
Switched to branch 'test'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (test)
$ git checkout dev
Switched to branch 'dev'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ git branch -d test
Deleted branch test (was ba76c20).

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ git stash save "Work in progress: Refactoring login module"
No local changes to save

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ git stash save "Work in progress: Refactoring login module"
No local changes to save

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ git add .

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ git stash save "Work in progress: Refactoring login module"
Saved working directory and index state On dev: Work in progress: Refactoring login module

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ git add .

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ <!DOCTYPE html>
bash: !DOCTYPE: event not found

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ <html lang="en">
bash: syntax error near unexpected token `newline'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ <head>
bash: syntax error near unexpected token `newline'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$     <meta charset="UTF-8">
bash: syntax error near unexpected token `newline'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$     <meta name="viewport" content="width=device-width, initial-scale=1.0">
bash: syntax error near unexpected token `newline'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$     <title>Home</title>
bash: syntax error near unexpected token `newline'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$     <link rel="stylesheet" href="styles.css">
bash: syntax error near unexpected token `newline'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ </head>
bash: syntax error near unexpected token `newline'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ <body>
bash: syntax error near unexpected token `newline'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$     <header>
bash: syntax error near unexpected token `newline'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$         <nav>
bash: syntax error near unexpected token `newline'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$             <a href="home.html" class="active">Home</a>
bash: syntax error near unexpected token `newline'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$             <a href="about.html">About</a>
bash: syntax error near unexpected token `newline'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$         </nav>
bash: syntax error near unexpected token `newline'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$     </header>
bash: syntax error near unexpected token `newline'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$     <main>
bash: syntax error near unexpected token `newline'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$         <section class="hero">
bash: syntax error near unexpected token `newline'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$             <h1>Welcome to Our Website</h1>
bash: syntax error near unexpected token `newline'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$             <p>Explore our content and join our growing community.</p>
bash: syntax error near unexpected token `newline'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$             <a href="about.html" class="button">Learn More</a>
bash: syntax error near unexpected token `newline'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$         </section>
bash: syntax error near unexpected token `newline'


UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$     </main>
bash: syntax error near unexpected token `newline'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$     <footer>
bash: syntax error near unexpected token `newline'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$         <p>&copy; 2024 Your Website. All rights reserved.</p>
bash: syntax error near unexpected token `newline'

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$     </footer>
bash: syntax error near unexpected token `newline'


UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ </body>
bash: syntax error near unexpected token `newline'


UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ </html>
bash: syntax error near unexpected token `newline'


UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ ^C

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ ^C

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ `git add .`

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ git stash save "Work in progress: Refactoring login module"
Saved working directory and index state On dev: Work in progress: Refactoring login module

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ `git stash pop`
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

Dropped refs/stash@{0} (ad1f3f7c929a607f209dac8872ef35519442eabe)

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ `git add .`

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ `git stash save "Work in progress: Refactoring login module"`
Saved working directory and index state On dev: Work in progress: Refactoring login module

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ `git stash list`
stash@{0}: On dev: Work in progress: Refactoring login module
stash@{1}: On dev: Work in progress: Refactoring login module

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ `git stash pop stash@{0}`
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html
        new file:   team.html

Dropped stash@{0} (ab1db9060d7421f469018f4a2b0e193b75008755)

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ `git add home.html`

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ `git commit -m "Restore changes for home.html"`
[dev 62de40e] Restore changes for home.html
 3 files changed, 125 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html
 create mode 100644 team.html


UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ `git push origin dev`
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 1.48 KiB | 505.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote: 
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/Umwizer/Gym-Git-Exercise-Solutions/pull/new/dev
remote:
To https://github.com/Umwizer/Gym-Git-Exercise-Solutions.git
 * [new branch]      dev -> dev

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ `git stash list`
stash@{0}: On dev: Work in progress: Refactoring login module

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ `git stash pop stash@{1}`
fatal: log for 'stash' only has 1 entries

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ `git reset --hard`
HEAD is now at 62de40e Restore changes for home.html

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)
$ `git push origin dev`
Everything up-to-date

UMWIZERWA@DESKTOP-6D0H2BN MINGW64 /c/TheGym/Github/Gym-Git-Exercise-Solutions (dev)