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

### Exercise 2

```bash

 thegym   ft/bundle-2  …  thegym  git  gym-git-exercise-solutions  git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git pull
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (1/1), 640 bytes | 320.00 KiB/s, done.
From https://github.com/Fidesnoella/gym-git-exercise-solutions
   65c8984..b69f6f3  main       -> origin/main
Updating 65c8984..b69f6f3
Fast-forward
 README.md     | 305 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
 about.html    |  12 +++++++
 home.html     |  12 +++++++
 services.html |  12 +++++++
 4 files changed, 341 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html
 create mode 100644 services.html
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   services.html

no changes added to commit (use "git add" and/or "git commit -a")
 thegym   main  …  thegym  git  gym-git-exercise-solutions  SIGHUP  git checkout -b ft/service-redesign
Switched to a new branch 'ft/service-redesign'
 thegym   ft/service-redesign  …  thegym  git  gym-git-exercise-solutions  git status
On branch ft/service-redesign
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   services.html

no changes added to commit (use "git add" and/or "git commit -a")
 thegym   ft/service-redesign  …  thegym  git  gym-git-exercise-solutions  git add .
 thegym   ft/service-redesign  …  thegym  git  gym-git-exercise-solutions  git commit -m "makes changes in services page"
[ft/service-redesign 302a02a] makes changes in services page
 1 file changed, 5 insertions(+)
 thegym   ft/service-redesign  …  thegym  git  gym-git-exercise-solutions  git push
fatal: The current branch ft/service-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/service-redesign

 thegym   ft/service-redesign  …  thegym  git  gym-git-exercise-solutions  128  git push --set-upstream origin ft/service-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 374 bytes | 187.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/service-redesign' on GitHub by visiting:
remote:      https://github.com/Fidesnoella/gym-git-exercise-solutions/pull/new/ft/service-redesign
remote:
To https://github.com/Fidesnoella/gym-git-exercise-solutions.git
 * [new branch]      ft/service-redesign -> ft/service-redesign
Branch 'ft/service-redesign' set up to track remote branch 'ft/service-redesign' from 'origin'.
 thegym   ft/service-redesign  …  thegym  git  gym-git-exercise-solutions  git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git add .
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git commit -m "Add new changes to service"
[main c808cdb] Add new changes to service
 1 file changed, 2 insertions(+), 1 deletion(-)
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 378 bytes | 126.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Fidesnoella/gym-git-exercise-solutions.git
   b69f6f3..c808cdb  main -> main
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git branch
  dev
  ft/bundle-2
  ft/service-redesign
* main
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git checkout ft/service-redesign
Switched to branch 'ft/service-redesign'
Your branch is up to date with 'origin/ft/service-redesign'.
 thegym   ft/service-redesign  …  thegym  git  gym-git-exercise-solutions  git merge main
Auto-merging services.html
CONFLICT (content): Merge conflict in services.html
Automatic merge failed; fix conflicts and then commit the result.
 thegym   ft/service-redesign  …  thegym  git  gym-git-exercise-solutions  SIGINT  git add .
 thegym   ft/service-redesign  …  thegym  git  gym-git-exercise-solutions  git commit -m "solving conflict"
[ft/service-redesign 2c9cb95] solving conflict
 thegym   ft/service-redesign  …  thegym  git  gym-git-exercise-solutions  git push
To https://github.com/Fidesnoella/gym-git-exercise-solutions.git
 ! [rejected]        ft/service-redesign -> ft/service-redesign (fetch first)
error: failed to push some refs to 'https://github.com/Fidesnoella/gym-git-exercise-solutions.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
 thegym   ft/service-redesign  …  thegym  git  gym-git-exercise-solutions  128  git fetch
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (1/1), 631 bytes | 631.00 KiB/s, done.
From https://github.com/Fidesnoella/gym-git-exercise-solutions
   302a02a..4a90c3a  ft/service-redesign -> origin/ft/service-redesign
 thegym   ft/service-redesign  …  thegym  git  gym-git-exercise-solutions  git push
To https://github.com/Fidesnoella/gym-git-exercise-solutions.git
 ! [rejected]        ft/service-redesign -> ft/service-redesign (non-fast-forward)
error: failed to push some refs to 'https://github.com/Fidesnoella/gym-git-exercise-solutions.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
 thegym   ft/service-redesign  …  thegym  git  gym-git-exercise-solutions  1  git pull
hint: You have divergent branches and need to specify how to reconcile them.
hint: You can do so by running one of the following commands sometime before
hint: your next pull:
hint:
hint:   git config pull.rebase false  # merge (the default strategy)
hint:   git config pull.rebase true   # rebase
hint:   git config pull.ff only       # fast-forward only
hint:
hint: You can replace "git config" with "git config --global" to set a default
hint: preference for all repositories. You can also pass --rebase, --no-rebase,
hint: or --ff-only on the command line to override the configured default per
hint: invocation.
fatal: Need to specify how to reconcile divergent branches.
 thegym   ft/service-redesign  …  thegym  git  gym-git-exercise-solutions  128  git config pull.rebase false
 thegym   ft/service-redesign  …  thegym  git  gym-git-exercise-solutions  git push
To https://github.com/Fidesnoella/gym-git-exercise-solutions.git
 ! [rejected]        ft/service-redesign -> ft/service-redesign (non-fast-forward)
error: failed to push some refs to 'https://github.com/Fidesnoella/gym-git-exercise-solutions.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
 thegym   ft/service-redesign  …  thegym  git  gym-git-exercise-solutions  1  git status
On branch ft/service-redesign
Your branch and 'origin/ft/service-redesign' have diverged,
and have 1 and 1 different commits each, respectively.
  (use "git pull" to merge the remote branch into yours)

nothing to commit, working tree clean
 thegym   ft/service-redesign  …  thegym  git  gym-git-exercise-solutions  git pull
Auto-merging services.html
CONFLICT (content): Merge conflict in services.html
Merge made by the 'ort' strategy.
 thegym   ft/service-redesign  …  thegym  git  gym-git-exercise-solutions  git status
On branch ft/service-redesign
Your branch is ahead of 'origin/ft/service-redesign' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
 thegym   ft/service-redesign  …  thegym  git  gym-git-exercise-solutions  git status
On branch ft/service-redesign
Your branch is ahead of 'origin/ft/service-redesign' by 2 commits.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean
 thegym   ft/service-redesign  …  thegym  git  gym-git-exercise-solutions  git add .
 thegym   ft/service-redesign  …  thegym  git  gym-git-exercise-solutions  git push
Enumerating objects: 2, done.
Counting objects: 100% (2/2), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 463 bytes | 463.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Fidesnoella/gym-git-exercise-solutions.git
   4a90c3a..eb0b76f  ft/service-redesign -> ft/service-redesign
 thegym   ft/service-redesign  …  thegym  git  gym-git-exercise-solutions  git status
On branch ft/service-redesign
Your branch is up to date with 'origin/ft/service-redesign'.

nothing to commit, working tree clean

```

## Bundle 3

### Exercise 1

```bash
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git checkout -b ft/team-page
Switched to a new branch 'ft/team-page'
 thegym   ft/team-page  …  thegym  git  gym-git-exercise-solutions  touch team.html
thegym   ft/team-page  …  thegym  git  gym-git-exercise-solutions   git add .
thegym   ft/team-page  …  thegym  git  gym-git-exercise-solutions   git commit -m "Add team page"
[ft/team-page (root-commit) e83f9a4] Add team page
 1 file changed, 12 insertions(+)
 create mode 100644 team.html
 thegym   ft/team-page  …  thegym  git  gym-git-exercise-solutions  git push origin ft/team-page
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 374 bytes | 187.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/team-page' on GitHub by visiting:
remote:      https://github.com/Fidesnoella/gym-git-exercise-solutions/pull/new/ft/team-page
remote:
To https://github.com/Fidesnoella/gym-git-exercise-solutions.git
 * [new branch]      ft/team-page -> ft/team-page
 thegym   ft/team-page  …  thegym  git  gym-git-exercise-solutions  git checkout main
Switched to branch 'main'
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git checkout -b ft/contact-page
Switched to a new branch 'ft/contact-page'
 thegym   ft/contact-page  …  thegym  git  gym-git-exercise-solutions  git branch
  dev
  ft/bundle-2
* ft/contact-page
  ft/service-redesign
  ft/team-page
  main
 thegym   ft/contact-page  …  thegym  git  gym-git-exercise-solutions  git checkout ft/team-page
M       README.md
Switched to branch 'ft/team-page'
Your branch is based on 'origin/ft/team-page', but the upstream is gone.
  (use "git branch --unset-upstream" to fixup)
 thegym   ft/team-page  …  thegym  git  gym-git-exercise-solutions  git log
commit d631d8c9377476500ca1a6ffaf458cbd7d4331cf (HEAD -> ft/team-page)
Author: Fidesnoella <fniragena@gmail.com>
Date:   Mon Nov 7 08:47:10 2022 +0200

    Add team page

commit be293f8232fac57d4684533135f0d12322b7ac83
Author: Fidesnoella <fniragena@gmail.com>
Date:   Mon Nov 7 08:43:03 2022 +0200

    Add team page

commit eb0b76f138576bc2116fb11b2611e1a3c31e5fc0 (origin/ft/service-redesign, ft/service-redesign)
Merge: 2c9cb95 4a90c3a
Author: Fidesnoella <fniragena@gmail.com>
Date:   Fri Nov 4 10:02:04 2022 +0200

    Merge branch 'ft/service-redesign' of https://github.com/Fidesnoella/gym-git-exercise-solutions into ft/service-redesign

commit 2c9cb9551ab12402aef1132b5a8d89ed2bf34eb0
Merge: 302a02a c808cdb
Author: Fidesnoella <fniragena@gmail.com>
Date:   Fri Nov 4 09:57:14 2022 +0200

    solving conflict


 thegym   ft/team-page  …  thegym  git  gym-git-exercise-solutions  SIGINT  git checkout ft/contact-page
M       README.md
Switched to branch 'ft/contact-page'
 thegym   ft/contact-page  …  thegym  git  gym-git-exercise-solutions  git cherry-pick d631d8c9377476500ca1a6ffaf458cbd7d4331cf
CONFLICT (modify/delete): team.html deleted in HEAD and modified in d631d8c (Add team page).  Version d631d8c (Add team page) of team.html left in tree.
error: could not apply d631d8c... Add team page
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git cherry-pick --continue".
hint: You can instead skip this commit with "git cherry-pick --skip".
hint: To abort and get back to the state before "git cherry-pick",
hint: run "git cherry-pick --abort".
 thegym   ft/contact-page  …  thegym  git  gym-git-exercise-solutions  1  git log
commit c808cdb13e62f5d186e2d30b423db878256d325f (HEAD -> ft/contact-page, origin/main, main)
Author: Fidesnoella <fniragena@gmail.com>
Date:   Fri Nov 4 08:43:46 2022 +0200

    Add new changes to service

commit b69f6f3a701f5c7107eeb77465289a06d303b4ec
Merge: 65c8984 bc88dbd
Author: Chrissie <chrissiemhrk@gmail.com>
Date:   Thu Nov 3 11:02:35 2022 +0200

    Merge pull request #1 from Fidesnoella/ft/bundle-2

    Add new html pages to the project

commit bc88dbd4697635e56066b2e99fb59ed156fed8a9 (origin/ft/bundle-2, ft/bundle-2)
Author: Fidesnoella <fniragena@gmail.com>
Date:   Tue Nov 1 20:35:17 2022 +0200

    Done with  bundle2 exercise1

 thegym   ft/contact-page  …  thegym  git  gym-git-exercise-solutions  touch contact.html
 thegym   ft/contact-page  …  thegym  git  gym-git-exercise-solutions  git status
On branch ft/contact-page
You are currently cherry-picking commit d631d8c.
  (fix conflicts and run "git cherry-pick --continue")
  (use "git cherry-pick --skip" to skip this patch)
  (use "git cherry-pick --abort" to cancel the cherry-pick operation)

Unmerged paths:
  (use "git add/rm <file>..." as appropriate to mark resolution)
        deleted by us:   team.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        contact.html

no changes added to commit (use "git add" and/or "git commit -a")
 thegym   ft/contact-page  …  thegym  git  gym-git-exercise-solutions  git add contact.html
 thegym   ft/contact-page  …  thegym  git  gym-git-exercise-solutions  git commit -m "add contact page"
[ft/contact-page bb2dcbd] add contact page
 Date: Mon Nov 7 08:47:10 2022 +0200
 2 files changed, 24 insertions(+)
 create mode 100644 contact.html
 create mode 100644 team.html
 thegym   ft/contact-page  …  thegym  git  gym-git-exercise-solutions  git push
fatal: The current branch ft/contact-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/contact-page

 thegym   ft/contact-page  …  thegym  git  gym-git-exercise-solutions  128  git push --set-upstream origin ft/contact-page
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 596 bytes | 596.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/Fidesnoella/gym-git-exercise-solutions/pull/new/ft/contact-page
remote:
To https://github.com/Fidesnoella/gym-git-exercise-solutions.git
 * [new branch]      ft/contact-page -> ft/contact-page
Branch 'ft/contact-page' set up to track remote branch 'ft/contact-page' from 'origin'.
 thegym   ft/contact-page  …  thegym  git  gym-git-exercise-solutions  SIGHUP  git checkout -b ft/faq-page
Switched to a new branch 'ft/faq-page'
 thegym   ft/faq-page  …  thegym  git  gym-git-exercise-solutions  touch faq.html
 thegym   ft/faq-page  …  thegym  git  gym-git-exercise-solutions  git status
On branch ft/faq-page
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        faq.html

no changes added to commit (use "git add" and/or "git commit -a")
 thegym   ft/faq-page  …  thegym  git  gym-git-exercise-solutions  git add faq.html
 thegym   ft/faq-page  …  thegym  git  gym-git-exercise-solutions  git commit -m "add faq page"
[ft/faq-page dafde93] add faq page
 1 file changed, 12 insertions(+)
 create mode 100644 faq.html
 thegym   ft/faq-page  …  thegym  git  gym-git-exercise-solutions  git push origin ft/faq-page
fatal: unable to access 'https://github.com/Fidesnoella/gym-git-exercise-solutions.git/': Could not resolve host: github.com
 thegym   ft/faq-page  …  thegym  git  gym-git-exercise-solutions  128  git push
fatal: The current branch ft/faq-page has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/faq-page

 thegym   ft/faq-page  …  thegym  git  gym-git-exercise-solutions  128  git push --set-upstream origin ft/faq-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 473 bytes | 94.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/faq-page' on GitHub by visiting:
remote:      https://github.com/Fidesnoella/gym-git-exercise-solutions/pull/new/ft/faq-page
remote:
To https://github.com/Fidesnoella/gym-git-exercise-solutions.git
 * [new branch]      ft/faq-page -> ft/faq-page
Branch 'ft/faq-page' set up to track remote branch 'ft/faq-page' from 'origin'.
 thegym   ft/faq-page  …  thegym  git  gym-git-exercise-solutions  git log
commit dafde93db1ad7618a9957ff7412835e9eebfd361 (HEAD -> ft/faq-page, origin/ft/faq-page)
Author: Fidesnoella <fniragena@gmail.com>
Date:   Mon Nov 7 10:41:08 2022 +0200

    add faq page

commit bb2dcbdda27dce1273e29c345f4fe88bc6f70bfd (origin/ft/contact-page, ft/contact-page)
Author: Fidesnoella <fniragena@gmail.com>
Date:   Mon Nov 7 08:47:10 2022 +0200

    add contact page

commit c808cdb13e62f5d186e2d30b423db878256d325f (origin/main, main)
Author: Fidesnoella <fniragena@gmail.com>
Date:   Fri Nov 4 08:43:46 2022 +0200

    Add new changes to service

commit b69f6f3a701f5c7107eeb77465289a06d303b4ec
Merge: 65c8984 bc88dbd
Author: Chrissie <chrissiemhrk@gmail.com>
Date:   Thu Nov 3 11:02:35 2022 +0200

 thegym   ft/faq-page  …  thegym  git  gym-git-exercise-solutions  git revert  b69f6f3a701f5c7107eeb77465289a06d303b4ec
error: commit b69f6f3a701f5c7107eeb77465289a06d303b4ec is a merge but no -m option was given.
fatal: revert failed
 thegym   ft/faq-page  …  thegym  git  gym-git-exercise-solutions  128  git log
commit dafde93db1ad7618a9957ff7412835e9eebfd361 (HEAD -> ft/faq-page, origin/ft/faq-page)
Author: Fidesnoella <fniragena@gmail.com>
Date:   Mon Nov 7 10:41:08 2022 +0200

    add faq page

commit bb2dcbdda27dce1273e29c345f4fe88bc6f70bfd (origin/ft/contact-page, ft/contact-page)
Author: Fidesnoella <fniragena@gmail.com>
Date:   Mon Nov 7 08:47:10 2022 +0200

    add contact page

commit c808cdb13e62f5d186e2d30b423db878256d325f (origin/main, main)
Author: Fidesnoella <fniragena@gmail.com>
Date:   Fri Nov 4 08:43:46 2022 +0200

    Add new changes to service

commit b69f6f3a701f5c7107eeb77465289a06d303b4ec
Merge: 65c8984 bc88dbd
 thegym   ft/faq-page  …  thegym  git  gym-git-exercise-solutions  git revert bb2dcbdda27dce1273e29c345f4fe88bc6f70bfd
[ft/faq-page 11db905] Revert "add contact page"
 2 files changed, 24 deletions(-)
 delete mode 100644 contact.html
 delete mode 100644 team.html
 thegym   ft/faq-page  …  thegym  git  gym-git-exercise-solutions 
 thegym   ft/faq-page  …  thegym  git  gym-git-exercise-solutions  git push
 Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 280 bytes | 280.00 KiB/s, done.
Total 2 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Fidesnoella/gym-git-exercise-solutions.git
   dafde93..11db905  ft/faq-page -> ft/faq-page
 thegym   ft/faq-page  …  thegym  git  gym-git-exercise-solutions 
```

### Exercise 2

```bash
 thegym   ft/faq-page  …  thegym  git  gym-git-exercise-solutions  git checkout -b ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'
 thegym   ft/home-page-redesign  …  thegym  git  gym-git-exercise-solutions  git checkout main
M       README.md
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git add home.html
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git commit -m "add home page content"
[main b5b9e80] add home page content
 1 file changed, 1 insertion(+)
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 331 bytes | 165.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Fidesnoella/gym-git-exercise-solutions.git
   c808cdb..b5b9e80  main -> main
 thegym   main  …  thegym  git  gym-git-exercise-solutions  git checkout ft/home-page-redesign
M       README.md
Switched to branch 'ft/home-page-redesign'
 thegym   ft/home-page-redesign  …  thegym  git  gym-git-exercise-solutions  git log
commit 11db9055002ca4a12f354e2eb3834390179439f1 (HEAD -> ft/home-page-redesign, origin/ft/faq-page, ft/faq-page)
Author: Fidesnoella <fniragena@gmail.com>
Date:   Mon Nov 7 10:44:45 2022 +0200

    Revert "add contact page"

    This reverts commit bb2dcbdda27dce1273e29c345f4fe88bc6f70bfd.

    :wq

commit dafde93db1ad7618a9957ff7412835e9eebfd361
Author: Fidesnoella <fniragena@gmail.com>
Date:   Mon Nov 7 10:41:08 2022 +0200

    add faq page

commit bb2dcbdda27dce1273e29c345f4fe88bc6f70bfd (origin/ft/contact-page, ft/contact-page)
Author: Fidesnoella <fniragena@gmail.com>
Date:   Mon Nov 7 08:47:10 2022 +0200

    add contact page

commit c808cdb13e62f5d186e2d30b423db878256d325f
Author: Fidesnoella <fniragena@gmail.com>
Date:   Fri Nov 4 08:43:46 2022 +0200

    Add new changes to service

commit b69f6f3a701f5c7107eeb77465289a06d303b4ec
Merge: 65c8984 bc88dbd
Author: Chrissie <chrissiemhrk@gmail.com>
Date:   Thu Nov 3 11:02:35 2022 +0200

    Merge pull request #1 from Fidesnoella/ft/bundle-2

    Add new html pages to the project

commit bc88dbd4697635e56066b2e99fb59ed156fed8a9 (origin/ft/bundle-2, ft/bundle-2)
Author: Fidesnoella <fniragena@gmail.com>
Date:   Tue Nov 1 20:35:17 2022 +0200

    Done with  bundle2 exercise1

commit abda73dcda1d4abe16d6346026e5719378c73b25
Author: Fidesnoella <fniragena@gmail.com>
Date:   Tue Nov 1 20:22:37 2022 +0200

    create service page

commit e6c0308be990e44b0ccc0e6803d84f4d8eab05dd (origin/dev, dev)
Author: Fidesnoella <fniragena@gmail.com>
Date:   Tue Nov 1 18:20:34 2022 +0200

    Bundle 1 Exercise 1&2

commit 56536b83b1bf86d371e189424c580001d23995e9
Author: Fidesnoella <fniragena@gmail.com>
Date:   Tue Nov 1 17:54:17 2022 +0200

    setup the home and about page

commit 65c89842992315502eb210dbbcf36cd868e43fb9
Author: Fidesnoella <fniragena@gmail.com>
Date:   Tue Nov 1 16:34:20 2022 +0200
 thegym   ft/home-page-redesign  …  thegym  git  gym-git-exercise-solutions  git rebase main
Successfully rebased and updated refs/heads/ft/home-page-redesign.
thegym   ft/home-page-redesign  …  thegym  git  gym-git-exercise-solutions  git log
commit 1011f66c0605366c3bdb2a4d5f5ff7df7a827bac (HEAD -> ft/home-page-redesign)
Author: Fidesnoella <fniragena@gmail.com>
Date:   Mon Nov 7 10:44:45 2022 +0200

    Revert "add contact page"

    This reverts commit bb2dcbdda27dce1273e29c345f4fe88bc6f70bfd.

    :wq

commit 28bf61a219a5826b01908e19f3a016aa2fdc1e74
Author: Fidesnoella <fniragena@gmail.com>
Date:   Mon Nov 7 10:41:08 2022 +0200

    add faq page

commit 00210a29a00cd9c47fb2bc870fb41b5e82e21800
Author: Fidesnoella <fniragena@gmail.com>
Date:   Mon Nov 7 08:47:10 2022 +0200

    add contact page

commit b5b9e80a19265eb75fb865a7e82e7419a3998a80 (origin/main, main)
Author: Fidesnoella <fniragena@gmail.com>
Date:   Mon Nov 7 11:20:33 2022 +0200

    add home page content

commit c808cdb13e62f5d186e2d30b423db878256d325f
Author: Fidesnoella <fniragena@gmail.com>
 thegym   ft/home-page-redesign  …  thegym  git  gym-git-exercise-solutions  git status
On branch ft/home-page-redesign
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   README.md
        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")
 thegym   ft/home-page-redesign  …  thegym  git  gym-git-exercise-solutions  git add home.html
 thegym   ft/home-page-redesign  …  thegym  git  gym-git-exercise-solutions  git commit -m "add list to home page"
[ft/home-page-redesign 1b4739a] add list to home page
 1 file changed, 5 insertions(+)
 thegym   ft/home-page-redesign  …  thegym  git  gym-git-exercise-solutions  git push
fatal: The current branch ft/home-page-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/home-page-redesign

 thegym   ft/home-page-redesign  …  thegym  git  gym-git-exercise-solutions  128  git push --set-upstream origin ft/home-page-redesign
Enumerating objects: 14, done.
Counting objects: 100% (14/14), done.
Delta compression using up to 4 threads
Compressing objects: 100% (12/12), done.
Writing objects: 100% (12/12), 1.42 KiB | 486.00 KiB/s, done.
Total 12 (delta 6), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (6/6), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/Fidesnoella/gym-git-exercise-solutions/pull/new/ft/home-page-redesign
remote:
To https://github.com/Fidesnoella/gym-git-exercise-solutions.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
Branch 'ft/home-page-redesign' set up to track remote branch 'ft/home-page-redesign' from 'origin'.
 thegym   ft/home-page-redesign  …  thegym  git  gym-git-exercise-solutions 
```
