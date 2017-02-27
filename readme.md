git:
mkdir MyProject (whatever you want)
cd MyProject
git init
//this innitialized the directory.  makes the x. part of zsh- not universal.  starts tracking //
touch readme.md
//makes a file.  readme.md is what you actually see in your github repo. md means markdown //
[put stuff in readme file (using sublime probably)]
git add . 
//must add before you can commit.//
commit -m "message here"
//must flag the m to add message to the commit //
create repo on github and grab the ssh link
//looks like git@githib.com:tiy-lv-frontend/MyProject.git this is the remote-not here but there (on server)//
add our remote
//git remote add origin git@githib.com:tiy-lv-frontend/MyProject.git //
git push origin master
// this is how you push to github.  pushing to branch master //

git add . 
git commit - "message"
gir push origin master 
//now that it is all done you just have to put three lines above to start pushing//





