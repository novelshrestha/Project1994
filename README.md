# Project1

c122616@SANVAXADM016 MINGW64 ~/Desktop/Project1
$ git init
Initialized empty Git repository in C:/Users/c122616/Desktop/Project1/.git/

c122616@SANVAXADM016 MINGW64 ~/Desktop/Project1 (master)
$ git add .

c122616@SANVAXADM016 MINGW64 ~/Desktop/Project1 (master)
$ git commit -m "my first project"
[master (root-commit) d873a44] my first project
 Committer: Novel Shrestha <Novel.Shrestha@monashhealth.org>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 34 insertions(+)
 create mode 100644 index.html

c122616@SANVAXADM016 MINGW64 ~/Desktop/Project1 (master)
$ git status
On branch master
nothing to commit, working tree clean

c122616@SANVAXADM016 MINGW64 ~/Desktop/Project1 (master)
$ git remote add origin https://github.com/novelstha/Project1.git

c122616@SANVAXADM016 MINGW64 ~/Desktop/Project1 (master)
$ git push origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 672 bytes | 672.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/novelstha/Project1/pull/new/master
remote:
To https://github.com/novelstha/Project1.git
 * [new branch]      master -> master

c122616@SANVAXADM016 MINGW64 ~/Desktop/Project1 (master)
$ ^C

c122616@SANVAXADM016 MINGW64 ~/Desktop/Project1 (master)
$
