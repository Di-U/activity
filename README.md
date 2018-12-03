C:\Users\user>mkdir activity

C:\Users\user>cd activity

C:\Users\user\activity>git status
fatal: not a git repository (or any of the parent directories): .git

C:\Users\user\activity>git init
Initialized empty Git repository in C:/Users/user/activity/.git/

C:\Users\user\activity>git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

C:\Users\user\activity>touch README.txt

C:\Users\user\activity>notepad README.txt

C:\Users\user\activity>git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)

        README.txt

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\user\activity>git add README.txt

C:\Users\user\activity>git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

        new file:   README.txt


C:\Users\user\activity>git commit -m "add readme"
[master (root-commit) 7e46804] add readme
 1 file changed, 1 insertion(+)
 create mode 100644 README.txt

C:\Users\user\activity>git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.txt

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\user\activity>git add -p
diff --git a/README.txt b/README.txt
index 23b2caf..7131c9b 100644
--- a/README.txt
+++ b/README.txt
@@ -1 +1 @@
-all about Github.
\ No newline at end of file
+all about Github, and how to use it.
\ No newline at end of file
Stage this hunk [y,n,q,a,d,e,?]? y


C:\Users\user\activity>git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        modified:   README.txt


C:\Users\user\activity>git commit -m "add how to use it"
[master 7d03458] add how to use it
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\Users\user\activity>git status
On branch master
nothing to commit, working tree clean

C:\Users\user\activity>touch learning-terminal.md

C:\Users\user\activity>notepad learning-terminal.md

C:\Users\user\activity>git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)

        learning-terminal.md

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\user\activity>git add learning-terminal.md

C:\Users\user\activity>git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   learning-terminal.md


C:\Users\user\activity>git commit -m "pwd command"
[master 511d6b4] pwd command
 1 file changed, 1 insertion(+)
 create mode 100644 learning-terminal.md

C:\Users\user\activity>git status
On branch master
nothing to commit, working tree clean

C:\Users\user\activity>git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   learning-terminal.md

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\user\activity>git add -p
diff --git a/learning-terminal.md b/learning-terminal.md
index 1970365..6611325 100644
--- a/learning-terminal.md
+++ b/learning-terminal.md
@@ -1 +1,2 @@
-pwd command
\ No newline at end of file
+pwd command
+ls command
\ No newline at end of file
Stage this hunk [y,n,q,a,d,e,?]? y


C:\Users\user\activity>git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        modified:   learning-terminal.md


C:\Users\user\activity>git commit -m "add ls command"
[master 656b6ca] add ls command
 1 file changed, 2 insertions(+), 1 deletion(-)

C:\Users\user\activity>touch our-teacher.txt

C:\Users\user\activity>notepad our-teacher.txt

C:\Users\user\activity>git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)

        our-teacher.txt

nothing added to commit but untracked files present (use "git add" to track)

C:\Users\user\activity>git add our-teacher.txt
C:\Users\user\activity>git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        new file:   our-teacher.txt


C:\Users\user\activity>git commit -m "add Emily Reese"
[master afe5ff8] add Emily Reese
 1 file changed, 1 insertion(+)
 create mode 100644 our-teacher.txt

C:\Users\user\activity>git status
On branch master
nothing to commit, working tree clean

C:\Users\user\activity>git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   our-teacher.txt

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\user\activity>git add -p
diff --git a/our-teacher.txt b/our-teacher.txt
index 278b266..f73801c 100644
--- a/our-teacher.txt
+++ b/our-teacher.txt
@@ -1 +1 @@
-Emily Reese
\ No newline at end of file
+Emily Reese, female.
\ No newline at end of file
Stage this hunk [y,n,q,a,d,e,?]? y


C:\Users\user\activity>git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

        modified:   our-teacher.txt


C:\Users\user\activity>git commit -m "add female"
[master bb1b05c] add female
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\Users\user\activity>git status
On branch master
nothing to commit, working tree clean

C:\Users\user\activity>
















