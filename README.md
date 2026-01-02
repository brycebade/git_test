# git_test
Hello Odin!

# git cheat sheet
<b>Cheatsheet</b>
<br>
<br>
This is a reference list of the most commonly used Git commands. Try to familiarize yourself with the commands so that you can eventually remember them all:
<br>
<br>
<b>Commands related to a remote repository:</b> 
<br>
<br>
<em>git clone git@github.com: USER-NAME/REPOSITORY-NAME.git</em><br>
<em>git push</em> or <em>git push origin main</em> (Both accomplish the same goal in this context)
<br>
<br>
<b>Commands related to the workflow:</b>
<br>
<br>
<em>git add .</em><br>
<em>git commit -m "A message describing what you have done to make this snapshot different"</em>
<br>
<br>
<b>Commands related to checking status or log history</b>
<br>
<br>
<em>git status</em><br>
<em>git log</em>
<br>
<br>
<b>The basic Git syntax is</b> <em>program | action | destination</em>.
<br>
<br>
For example,
<br>
<br>
<em>git add .</em> is read as <em>git | add | .</em>, where the period represents everything in the current directory;<br>
<em>git commit -m "message"</em> is read as <em>git | commit -m | "message"</em>; and<br>
<em>git status</em> is read as <em>git | status | (no destination)</em>.