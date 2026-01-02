# git_test
Hello Odin!

# git cheat sheet
Cheatsheet<br>
This is a reference list of the most commonly used Git commands. (You might consider bookmarking this handy page.) Try to familiarize yourself with the commands so that you can eventually remember them all:
<br>
Commands related to a remote repository: <br>
git clone git@github.com:USER-NAME/REPOSITORY-NAME.git<br>
git push or git push origin main (Both accomplish the same goal in this context)<br>
Commands related to the workflow:<br>
git add .<br>
git commit -m "A message describing what you have done to make this snapshot different"<br>
Commands related to checking status or log history<br>
git status<br>
git log<br>
The basic Git syntax is program | action | destination.<br>

For example,<br>
<br>
git add . is read as git | add | ., where the period represents everything in the current directory;<br>
git commit -m "message" is read as git | commit -m | "message"; and<br>
git status is read as git | status | (no destination).