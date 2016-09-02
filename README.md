# learngit
This repository for myself to learn git.

Can not push master to origin:


guo@ubuntu16:~/learngit$ git push   origin master
To git@github.com:Brian-It/learngit.git
 ! [rejected]        master -> master (non-fast-forward)
error: failed to push some refs to 'git@github.com:Brian-It/learngit.git'
hint: Updates were rejected because the tip of your current branch is behind
hint: its remote counterpart. Integrate the remote changes (e.g.
hint: 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.


result:
      #pull=fetch+merge
      git pull --rebase origin master
      
