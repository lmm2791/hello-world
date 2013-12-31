$ mkdir ~/hello-world
# creates a directory for the project called "hello-world" in your user directory

$ cd ~/hello-world
# changes the current working directory to the newly created directory

$ git init
# sets up the necessary git files

$ touch README
# creates a file called "README" in your hello-world directory

$ git add README
# stages your README file, adding it to the list of files to be committed

$ git commit -m 'first commit'
# commits your files, adding the message "first commit"

$ git remote add origin https://github.com/lmm2791/hello-world.git
# creates a remote named "origin" pointing at your github repository

$ git push origin master
# sends your commits in the "master" branch to github
