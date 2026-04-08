### Welcome to LBSA's GitHub page! 🤖🐟🦭

This group is intended to make sharing lab-wide repositories easier and for publishing public repositories to accompany publications. 

#### Transfering Repositories
To transfer repositories into the group organization you can use the "Transfer Repository" setting in your own repository (Transfer to the group @Drexel-LBSA). Alternatively, if you're transfering a repo from outside of Github, you can do the following:
`
cd $HOME/{wherever the code is stored}
git remote rename origin {origin name}
git remote add origin https://github.com/{your username}/{name of repo}.git
git push origin master
git remote rm {original location}
`
