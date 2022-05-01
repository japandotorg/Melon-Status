## Are you updating? Use these commands

Download your site with all the directories. `git clone --recursive <your repo link goes here>`

Update the cState theme submodule. `git submodule foreach git pull origin master`

In the parent directory, type `hugo serve`. Check to see if everything is working.

Then do `git add -A; git commit -m "Update cState"; git push origin <branch, probably main or master>`. Your status page is now updated and uploaded.


## For maintainers (probably not for you)

Maintainers need to update both cstate/cstate and cstate/example for each new version.

Download this repo with all the directories. `git clone --recursive -b dev https://github.com/japandotorg/Melon-Status.git`

Add your changes from cstate/cstate's exampleSite folder.

Update the cState theme submodule. `git submodule foreach git pull origin master`

Then push `git add -A; git commit -m "Update cState vX.X.X"; git push origin master`.
