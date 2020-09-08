#git test
- Using Windows GUI or command line create a folder where you want your local repo to be stored physically
- open VS and File/Open the folder. This creates a .vs dir
- create a readme.md file under the folder. Right click on folder in Solution Explorer, Add/NewFile.
- View/Terminal. It opens at the directory path.
- from the terminal run git init and a .git hidden file is created.
- run git status to see that the files are not tracked.
- run git add readme.md to start tracking.
- always run git status after each command.
- run git reset to untrack again.
- run git add . to track all files.
- run git commit -m "First commit to local repo".
- run git status and git log.
- change and save the readme.md file.
- run git status to see that the file has been modified, as git is tracking the changes, but the change is not staged yet, RED.
- run git add . and see that the file is now staged and ready to be commited, GREEN.
- run git commit -m "Second Commit of changed readme.md file".
- run gh auth login to log into account.
- run gh repo create RobbinLawDMIT2018/gittest4.
- go via browser to github to see that the repo was created, but no files in repo.
- run git remote -v to see that the local repo is connected to the remote.
- run git push -u origin master to push the local repo to the remote.
- go via browser to github to see that the repo was changed and files were added.
- change and save the readme.md file and run git status to see that it has changed.
- run git add . then git commit -m "Third Commit" then push -u origin master, running git status after each.
- go via browser to github to see that the repo was changed.