# ps-1
1.
player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo
$ git init
Initialized empty Git repository in C:/Users/yogamber singh negi/Desktop/`repo/.git/

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ echo "my name is yogamber" >> first

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git add .

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   first


player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git commit -m "first commit done"
[master (root-commit) 360bc93] first commit done
 1 file changed, 1 insertion(+)
 create mode 100644 first

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git remote add origin https://github.com/yogamber1/ps-1.git

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 231 bytes | 46.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/yogamber1/ps-1.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git branch feature

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git branch dev

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git branch qa

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git branch delivery

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git branch prod

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git branch
  delivery
  dev
  feature
* master
  prod
  qa

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git push -u origin feature
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'feature' on GitHub by visiting:
remote:      https://github.com/yogamber1/ps-1/pull/new/feature
remote:
To https://github.com/yogamber1/ps-1.git
 * [new branch]      feature -> feature
Branch 'feature' set up to track remote branch 'feature' from 'origin'.

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git push -u origin dev
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/yogamber1/ps-1/pull/new/dev
remote:
To https://github.com/yogamber1/ps-1.git
 * [new branch]      dev -> dev
Branch 'dev' set up to track remote branch 'dev' from 'origin'.
player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git push -u origin qa
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'qa' on GitHub by visiting:
remote:      https://github.com/yogamber1/ps-1/pull/new/qa
remote:
To https://github.com/yogamber1/ps-1.git
 * [new branch]      qa -> qa
Branch 'qa' set up to track remote branch 'qa' from 'origin'.

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git push -u origin delivery
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'delivery' on GitHub by visiting:
remote:      https://github.com/yogamber1/ps-1/pull/new/delivery
remote:
To https://github.com/yogamber1/ps-1.git
 * [new branch]      delivery -> delivery
Branch 'delivery' set up to track remote branch 'delivery' from 'origin'.

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git push -u origin prod
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'prod' on GitHub by visiting:
remote:      https://github.com/yogamber1/ps-1/pull/new/prod
remote:
To https://github.com/yogamber1/ps-1.git
 * [new branch]      prod -> prod
Branch 'prod' set up to track remote branch 'prod' from 'origin'.

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git checkout feature
Switched to branch 'feature'
Your branch is up to date with 'origin/feature'.

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (feature)
$ mkdir inside_feature

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (feature)
$ cd
.git/           first           inside_feature/

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (feature)
$ cd
.git/           first           inside_feature/

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (feature)
$ cd
.git/           first           inside_feature/

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (feature)
$ cd inside_feature

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo/inside_feature (feature)
$ echo "we are inside feature" >> another.txt

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo/inside_feature (feature)
$ git status
On branch feature
Your branch is up to date with 'origin/feature'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        ./

nothing added to commit but untracked files present (use "git add" to track)

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo/inside_feature (feature)
$ cd ..

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (feature)
$ git status
On branch feature
Your branch is up to date with 'origin/feature'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        inside_feature/

nothing added to commit but untracked files present (use "git add" to track)

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (feature)
$ git add .

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (feature)
$ git commit -m "commit for feature"
[feature a16962c] commit for feature
 1 file changed, 1 insertion(+)
 create mode 100644 inside_feature/another.txt

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (feature)
$ git p
prune   pull    push

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (feature)
$ git push -u origin feature
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 353 bytes | 88.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/yogamber1/ps-1.git
   360bc93..a16962c  feature -> feature
Branch 'feature' set up to track remote branch 'feature' from 'origin'.

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (feature)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git ls-tree -r master
100644 blob 5d08ad9df3b8132c8c293f4f3f2c569901e65bcf    first

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git pull origin master
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (1/1), 631 bytes | 12.00 KiB/s, done.
From https://github.com/yogamber1/ps-1
 * branch            master     -> FETCH_HEAD
   360bc93..e99ecd8  master     -> origin/master
Updating 360bc93..e99ecd8
Fast-forward
 inside_feature/another.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 inside_feature/another.txt

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git diff

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git ls-tree -r master
100644 blob 5d08ad9df3b8132c8c293f4f3f2c569901e65bcf    first
100644 blob a037eacec998779b81023343f3e0930500582664    inside_feature/another.txt

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git ls-tree -r delivery
100644 blob 5d08ad9df3b8132c8c293f4f3f2c569901e65bcf    first

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git checkout delivery
Switched to branch 'delivery'
Your branch is up to date with 'origin/delivery'.

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (delivery)
$ git pull origin master
From https://github.com/yogamber1/ps-1
 * branch            master     -> FETCH_HEAD
Updating 360bc93..e99ecd8
Fast-forward
 inside_feature/another.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 inside_feature/another.txt

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (delivery)
$ git pull origin delivery
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (2/2), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 675 bytes | 2.00 KiB/s, done.
From https://github.com/yogamber1/ps-1
 * branch            delivery   -> FETCH_HEAD
   360bc93..9baa700  delivery   -> origin/delivery
Merge made by the 'recursive' strategy.
 check.txt | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 check.txt

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (delivery)
$ git ls-tree -r delivery
100644 blob ed6066db73721ae9c9e0256cf0a3a45e1499ce17    check.txt
100644 blob 5d08ad9df3b8132c8c293f4f3f2c569901e65bcf    first
100644 blob a037eacec998779b81023343f3e0930500582664    inside_feature/another.txt

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (delivery)
$ git push -u origin delivery
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 375 bytes | 125.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/yogamber1/ps-1.git
   9baa700..be5735f  delivery -> delivery
Branch 'delivery' set up to track remote branch 'delivery' from 'origin'.

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (delivery)
$ git status
On branch delivery
Your branch is up to date with 'origin/delivery'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   first

no changes added to commit (use "git add" and/or "git commit -a")

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (delivery)
$ git add first

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (delivery)
$ git status
On branch delivery
Your branch is up to date with 'origin/delivery'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   first


player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (delivery)
$ git commit
Aborting commit due to empty commit message.

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (delivery)
$ git commit -m "updated"
[delivery 17714a3] updated
 1 file changed, 1 insertion(+)

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (delivery)
$ git status
On branch delivery
Your branch is ahead of 'origin/delivery' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (delivery)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ type first
bash: type: first: not found

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ vim first

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git diff
diff --git a/first b/first
index 5d08ad9..e8ea178 100644
--- a/first
+++ b/first
@@ -1 +1,2 @@
-my name is yogamber
+my name is yogamber
+singh negi

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git add first

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git commit -m "updated"
[master cf1767f] updated
 1 file changed, 2 insertions(+), 1 deletion(-)

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git status
On branch master
Your branch is ahead of 'origin/master' by 1 commit.
  (use "git push" to publish your local commits)

nothing to commit, working tree clean

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$ git push origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 308 bytes | 308.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/yogamber1/ps-1.git
   e99ecd8..cf1767f  master -> master

player x@DHINCHIKKIPC MINGW64 ~/Desktop/`repo (master)
$
