ubuntu $ git init
Initialized empty Git repository in /root/.git/
ubuntu $ git clone https://github.com/fcurcho/clase-maq-virtuales.git
Cloning into 'clase-maq-virtuales'...
Username for 'https://github.com': frurcho
Password for 'https://frurcho@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/fcurcho/clase-maq-virtuales.git/'
ubuntu $ git clone https://github.com/fcurcho/clase-maq-virtuales.git
Cloning into 'clase-maq-virtuales'...
Username for 'https://github.com': fcurcho
Password for 'https://fcurcho@github.com': 
remote: Write access to repository not granted.
fatal: unable to access 'https://github.com/fcurcho/clase-maq-virtuales.git/': The requested URL returned error: 403
ubuntu $ git clone https://github.com/fcurcho/clase-maq-virtuales.git
Cloning into 'clase-maq-virtuales'...
Username for 'https://github.com': fcurcho
Password for 'https://fcurcho@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/fcurcho/clase-maq-virtuales.git/'
ubuntu $ echo "# IntroMV" >> README.md
ubuntu $ git init
Reinitialized existing Git repository in /root/.git/
ubuntu $ git add README.md
ubuntu $ git commit -m "first commit"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'root@ubuntu.(none)')
ubuntu $ git branch -M main
error: refname refs/heads/master not found
fatal: Branch rename failed
ubuntu $ git remote add origin https://github.com/fcurcho/IntroMV.git
ubuntu $ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/fcurcho/IntroMV.git'
ubuntu $ echo "# IntroMV" >> README.md
ubuntu $ git init
Reinitialized existing Git repository in /root/.git/
ubuntu $ git add README.md
ubuntu $ git commit -m "primer commit"

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'root@ubuntu.(none)')
ubuntu $ git config --global user.email "florldr176@gmail.com"
ubuntu $ git config --global user.name "fcurcho"              
ubuntu $ nano
ubuntu $ ls 
README.md  filesystem
ubuntu $ nano README.md


Use "fg" to return to nano.

[1]+  Stopped                 nano README.md
ubuntu $ fg
nano README.md
ubuntu $ ls 
README.md  README.txt  filesystem
ubuntu $ git add .
ubuntu $ git commit -m "agregando readme.txt"
[master (root-commit) 61db98b] agregando readme.txt
 14 files changed, 204 insertions(+)
 create mode 100644 .bash_history
 create mode 100644 .bashrc
 create mode 100644 .gitconfig
 create mode 100644 .profile
 create mode 100644 .ssh/authorized_keys
 create mode 100644 .ssh/id_rsa
 create mode 100644 .ssh/id_rsa.pub
 create mode 100644 .ssh/known_hosts
 create mode 100644 .theia/recentworkspace.json
 create mode 100644 .theia/settings.json
 create mode 100644 .vimrc
 create mode 100644 README.md
 create mode 100644 README.txt
 create mode 120000 filesystem
ubuntu $ git push
fatal: The current branch master has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin master

ubuntu $ git push origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/fcurcho/IntroMV.git'
ubuntu $ git push origin master
Username for 'https://github.com': fcurcho
Password for 'https://fcurcho@github.com': 
remote: Support for password authentication was removed on August 13, 2021.
remote: Please see https://docs.github.com/en/get-started/getting-started-with-git/about-remote-repositories#cloning-with-https-urls for information on currently recommended modes of authentication.
fatal: Authentication failed for 'https://github.com/fcurcho/IntroMV.git/'
ubuntu $ git push origin master
Username for 'https://github.com': fcurcho
Password for 'https://fcurcho@github.com': 
Enumerating objects: 18, done.
Counting objects: 100% (18/18), done.
Compressing objects: 100% (14/14), done.
Writing objects: 100% (18/18), 5.23 KiB | 1.74 MiB/s, done.
Total 18 (delta 1), reused 0 (delta 0)
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/fcurcho/IntroMV.git
 * [new branch]      master -> master
