### Welcome to LBSA's GitHub page! 🤖🐟🦭

This group is intended to make sharing lab-wide repositories easier and for publishing public repositories to accompany publications. 

#### Transfering Repositories from LOCAL code
To initialize a set of code into a GitHub repository, 
1. Go to the "Repositories" page of Drexel-LBSA
2. Click "Create New Repository"
3. Fill out details, such as name of the repo and visability settings
4. Use command line to create local repository and push to the remote one you've just created!<code>
  cd {wherever the code is stored}
  git init
  git config --global user.name "{your github username}"
  git add .
  git commit -m "first commit"
  git branch -M main
  git remote add origin https://github.com/Drexel-LBSA/{name of repo on github}.git
  git push -u origin main</code>

#### Transfering Repositories from EXISTING GitHub repos
To transfer repositories into the group organization you can use the "Transfer Repository" setting in your own repository (Transfer to the group @Drexel-LBSA). Alternatively, if you're transfering a repo from outside of Github, you can do the following:
<code>
  cd $HOME/{wherever the code is stored}
  git remote rename origin {origin name}
  git remote add origin https://github.com/{your username}/{name of repo}.git
  git push origin master
  git remote rm {original location}</code>
