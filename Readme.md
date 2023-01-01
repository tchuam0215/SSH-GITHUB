This repo is a test, on how to share your local git repo/project with github : 
1. Create an ssh key. 
2. share the public key with github.
3. Then do a git init to initialize the repository as a git repository.
4. Push the local repo with changes to github via ssh. 
5. do some git command (status log commit and check the changes to the remote repo).

# command used in this repository :

- 

  409  cd C:\Users\tchua\Desktop\Python\SSH-Github
  410  git add . 
  411  git commit -m "First update"
  412  git remote add origin git@github.com:tchuam0215/SSH-GITHUB.git   # Add a remote repository to your local git repo, the remote git repo should already exist 
  413  git branch
  414  git branch --help
  415  git push -u origin master # push change from your local repository to your remote repository
  416  cd #/.ssh
  417  cd ~/.ssh
  418  ssh-keygen -o -t rsa -C "ch.tchuenkam@gmail.com"
  419  cat id_rsa_ssh_github.pub
  420  ssh -T git@github.com # test the ssh key connection
  421  ls -al
  422  eval "$(ssh-agent -s)"
  423  ssh-add ~/.ssh/id_rsa_ssh_github
  424  ssh -T git@github.com
  425  ls ~/.ssh/
  426  ssh -T GITHUB-tchuam0215@github.com
  427  ssh -T github-tchuam0215@github.com
  428  ssh -vT git@github.com
  429  ssh-add -l -E sha256
  430  git add .
  431  cd c/Users/tchua/Desktop/Python/SSH-Github
  432  cd /mnt/c/Users/tchua/Desktop/Python/SSH-Github
  433  git add .
  434  git commit -m "Readme.md file updated"
  435  git push -u origin master
  436  ssh-add -l -E sha256
  437  git status
  438  git branch
  439  git pull origin master
