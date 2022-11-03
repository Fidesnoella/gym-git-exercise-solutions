# Git exercise project

This project will be used for a series of git exercises

## Bundle 1

### Exercise 1

```bash
thegym  …  thegym  git  gym-git-exercise-solutions  code .
 thegym  …  thegym  git  gym-git-exercise-solutions  git init
hint: Using 'master' as the name for the initial branch. This default branch name
hint: is subject to change. To configure the initial branch name to use in all
hint: of your new repositories, which will suppress this warning, call:
hint:
hint: 	git config --global init.defaultBranch <name>
hint:
hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
hint: 'development'. The just-created branch can be renamed via this command:
hint:
hint: 	git branch -m <name>
Initialized empty Git repository in /home/thegym/code/thegym/git/gym-git-exercise-solutions/.git/
 thegym   master  …  thegym  git  gym-git-exercise-solutions  git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)
 thegym   master  …  thegym  git  gym-git-exercise-solutions  git branch -M main
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git status
On branch main

No commits yet

nothing to commit (create/copy files and use "git add" to track)
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	README.md

nothing added to commit but untracked files present (use "git add" to track)
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git add .
 thegym   main  …  thegym  git  gym-git-exercise-solutions   git add README.md
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git commit -m "init project"
[main (root-commit) 65c8984] init project
 1 file changed, 3 insertions(+)
 create mode 100644 README.md
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git remote add origin https://github.com/Fidesnoella/gym-git-exercise-solutions.git
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git status
On branch main
nothing to commit, working tree clean
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git push
fatal: The current branch main has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin main

 thegym   main  …  thegym  git  gym-git-exercise-solutions  128  git push --set-upstream origin main
Username for 'https://github.com': Fidesnoella
Password for 'https://Fidesnoella@github.com':
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 278 bytes | 139.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Fidesnoella/gym-git-exercise-solutions.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git push
Username for 'https://github.com': Fidesnoella
Password for 'https://Fidesnoella@github.com':
Everything up-to-date
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git checkout -b  dev
Switched to a new branch 'dev'
 thegym   dev  …  thegym  git  gym-git-exercise-solutions  git status
On branch dev
nothing to commit, working tree clean
 thegym   dev  …  thegym  git  gym-git-exercise-solutions  git push origin dev
Username for 'https://github.com': Fidesnoella
Password for 'https://Fidesnoella@github.com':
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/Fidesnoella/gym-git-exercise-solutions.git/'
 thegym   dev  …  thegym  git  gym-git-exercise-solutions  128  git push origin dev
Username for 'https://github.com': Fidesnoella
Password for 'https://Fidesnoella@github.com':
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/Fidesnoella/gym-git-exercise-solutions/pull/new/dev
remote:
To https://github.com/Fidesnoella/gym-git-exercise-solutions.git
 * [new branch]      dev -> dev
 thegym   dev  …  thegym  git  gym-git-exercise-solutions  git checkout -b test
Switched to a new branch 'test'
 thegym   test  …  thegym  git  gym-git-exercise-solutions  git push origin test
Username for 'https://github.com': Fidesnoella
Password for 'https://Fidesnoella@github.com':
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'test' on GitHub by visiting:
remote:      https://github.com/Fidesnoella/gym-git-exercise-solutions/pull/new/test
remote:
To https://github.com/Fidesnoella/gym-git-exercise-solutions.git
 * [new branch]      test -> test
 thegym   test  …  thegym  git  gym-git-exercise-solutions  git checkout dev
Switched to branch 'dev'
 thegym   dev  …  thegym  git  gym-git-exercise-solutions  git branch -D test
Deleted branch test (was 65c8984).
 thegym   dev  …  thegym  git  gym-git-exercise-solutions  git push origin --delete test
Username for 'https://github.com': Fidesnoella
Password for 'https://Fidesnoella@github.com':
To https://github.com/Fidesnoella/gym-git-exercise-solutions.git
 - [deleted]         test
 thegym   dev  …  thegym  git  gym-git-exercise-solutions 

```

### Exercise 2

```bash
thegym   dev  …  thegym  git  gym-git-exercise-solutions  touch home.html
thegym   dev  …  thegym  git  gym-git-exercise-solutions  git status
On branch dev
Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified: README.md

Untracked files:
(use "git add <file>..." to include in what will be committed)
home.html

no changes added to commit (use "git add" and/or "git commit -a")
thegym   dev  …  thegym  git  gym-git-exercise-solutions  git stash list
thegym   dev  …  thegym  git  gym-git-exercise-solutions  git add home.html
thegym   dev  …  thegym  git  gym-git-exercise-solutions  git status
On branch dev
Changes to be committed:
(use "git restore --staged <file>..." to unstage)
new file: home.html

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified: README.md

thegym   dev  …  thegym  git  gym-git-exercise-solutions  git stash
Saved working directory and index state WIP on dev: 65c8984 init project
thegym   dev  …  thegym  git  gym-git-exercise-solutions  git list
git: 'list' is not a git command. See 'git --help'.

The most similar commands are
bisect
rev-list
thegym   dev  …  thegym  git  gym-git-exercise-solutions  1  git stash list
stash@{0}: WIP on dev: 65c8984 init project
thegym   dev  …  thegym  git  gym-git-exercise-solutions  touch about.html
thegym   dev  …  thegym  git  gym-git-exercise-solutions  git add about.html
thegym   dev  …  thegym  git  gym-git-exercise-solutions  git stash
Saved working directory and index state WIP on dev: 65c8984 init project
thegym   dev  …  thegym  git  gym-git-exercise-solutions  SIGHUP  git stash list
stash@{0}: WIP on dev: 65c8984 init project
stash@{1}: WIP on dev: 65c8984 init project
thegym   dev  …  thegym  git  gym-git-exercise-solutions  touch team.html
thegym   dev  …  thegym  git  gym-git-exercise-solutions  git status
On branch dev
Untracked files:
(use "git add <file>..." to include in what will be committed)
team.html

nothing added to commit but untracked files present (use "git add" to track)
thegym   dev  …  thegym  git  gym-git-exercise-solutions  git add team.html
thegym   dev  …  thegym  git  gym-git-exercise-solutions  git stash
Saved working directory and index state WIP on dev: 65c8984 init project
thegym   dev  …  thegym  git  gym-git-exercise-solutions  git stash list
stash@{0}: WIP on dev: 65c8984 init project
stash@{1}: WIP on dev: 65c8984 init project
stash@{2}: WIP on dev: 65c8984 init project
thegym   dev  …  thegym  git  gym-git-exercise-solutions  1  git stash pop stash@{1}
On branch dev
Changes to be committed:
(use "git restore --staged <file>..." to unstage)
new file: about.html

Dropped stash@{1} (ab84f4ed916e35de37249afda5b868a053a8c8b5)
thegym   dev  …  thegym  git  gym-git-exercise-solutions  1  git stash list
stash@{0}: WIP on dev: 65c8984 init project
stash@{1}: WIP on dev: 65c8984 init project
thegym   dev  …  thegym  git  gym-git-exercise-solutions  git stash pop stash@{1}
On branch dev
Changes to be committed:
(use "git restore --staged <file>..." to unstage)
new file: about.html
new file: home.html

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified: README.md

Dropped stash@{1} (aeb381a0d9ff7c4a2f12442a09a6e0fcd129c1d4)
thegym   dev  …  thegym  git  gym-git-exercise-solutions  git add about.html home.html
thegym   dev  …  thegym  git  gym-git-exercise-solutions  git status
On branch dev
Changes to be committed:
(use "git restore --staged <file>..." to unstage)
new file: about.html
new file: home.html

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified: README.md

thegym   dev  …  thegym  git  gym-git-exercise-solutions  git commit -m "setup the home and about page"
[dev 56536b8] setup the home and about page
2 files changed, 24 insertions(+)
create mode 100644 about.html
create mode 100644 home.html
thegym   dev  …  thegym  git  gym-git-exercise-solutions  git push origin dev
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 583 bytes | 583.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Fidesnoella/gym-git-exercise-solutions.git
65c8984..56536b8 dev -> dev
thegym   dev  …  thegym  git  gym-git-exercise-solutions  git status
On branch dev
Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified: README.md

no changes added to commit (use "git add" and/or "git commit -a")
thegym   dev  …  thegym  git  gym-git-exercise-solutions  git stash list
stash@{0}: WIP on dev: 65c8984 init project
thegym   dev  …  thegym  git  gym-git-exercise-solutions  git stash pop
On branch dev
Changes to be committed:
(use "git restore --staged <file>..." to unstage)
new file: team.html

Changes not staged for commit:
(use "git add <file>..." to update what will be committed)
(use "git restore <file>..." to discard changes in working directory)
modified: README.md

Dropped refs/stash@{0} (f0a2a10649557b1988b4ca197e58000f77c50582)
thegym   dev  …  thegym  git  gym-git-exercise-solutions  git reset --hard
HEAD is now at 56536b8 setup the home and about page
thegym   dev  …  thegym  git  gym-git-exercise-solutions 
```

## Bundle 2

### Exercise 1

```bash

On branch dev
nothing to commit, working tree clean
 thegym   dev  …  thegym  git  gym-git-exercise-solutions  git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'
 thegym   ft/bundle-2  …  thegym  git  gym-git-exercise-solutions  git status
On branch ft/bundle-2
nothing to commit, working tree clean
 thegym   ft/bundle-2  …  thegym  git  gym-git-exercise-solutions  touch services.html
 thegym   ft/bundle-2  …  thegym  git  gym-git-exercise-solutions  git status
On branch ft/bundle-2
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        services.html

nothing added to commit but untracked files present (use "git add" to track)
 thegym   ft/bundle-2  …  thegym  git  gym-git-exercise-solutions  git add services.html
 thegym   ft/bundle-2  …  thegym  git  gym-git-exercise-solutions  git commit -m "create service page"
[ft/bundle-2 abda73d] create service page
 1 file changed, 12 insertions(+)
 create mode 100644 services.html
 thegym   ft/bundle-2  …  thegym  git  gym-git-exercise-solutions  git push origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 489 bytes | 244.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/Fidesnoella/gym-git-exercise-solutions/pull/new/ft/bundle-2
remote:
To https://github.com/Fidesnoella/gym-git-exercise-solutions.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2
 thegym   ft/bundle-2  …  thegym  git  gym-git-exercise-solutions  git status
On branch ft/bundle-2
nothing to commit, working tree clean
 thegym   ft/bundle-2  …  thegym  git  gym-git-exercise-solutions 

```
