Created Project sshTestMe

allowed XCode 5 to create a GIT repo in project

NOTE: to use ssh follow directions at https://github.com/settings/ssh

Created a repo sshTestMe on github set to ssh

in terminal
cd {fullpath}/TestMe 
git remote add origin git@github.com:BarryNelson/sshTestMe.git
git push -u origin master
NOTE: it will not work if you don't have the ssh key configured properly

Now project is now tied into the github repository.
Commit, Push, Pull, etc should work now.