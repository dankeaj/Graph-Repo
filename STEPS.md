Step 0:<br>
created repo on github which provided initial commit.<br>

Step 1:<br>
git add README.md<br>
git add STEPS.md<br>
git commit -m "Step 1."<br>
git push -u origin main<br>

Step 2:<br>
git add STEPS.md<br>
git commit -m "Step 2."<br>
git push -u origin main<br>

Step 3:<br> 
git add STEPS.md<br>
git commit -m "Step 3."<br>
git push -u origin bug-fix<br>

Step 4:<br> 
git add STEPS.md<br>
git commit -m "Step 4."<br>
git push -u origin bug-fix<br>
git checkout -b bug-fix-experimental<br>

Step 5:<br> 
git checkout bug-fix<br>
git merge main<br>
manually resolved merge conflict inside STEPS.md<br>
git add STEPS.md<br>
git commit -m "Step 5."<br>
git push -u origin bug-fix<br>

Step 6:<br>
git add STEPS.md<br>
git commit -m "Step 6."<br>
git push -u origin bug-fix<br>

Step 7:<br>
Added image<br>
![Headache](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fi.imgflip.com%2F471xbc.jpg&f=1&nofb=1&ipt=0f8ac697eb153de179896f999f481de8e7cf42597802a218ee2b42a52c2cea88&ipo=images "Merge Conflicts")<br>
git add STEPS.md<br>
git commit -m "Step 7."<br>
git push -u origin bug-fix-experimental<br>

Step 8:<br> 
git add STEPS.md<br>
git commit -m "Step 8."<br>
git push -u origin bug-fix<br>

Step 9:<br> 
git add STEPS.md<br>
git commit -m "Step 9."<br>
git push -u origin bug-fix<br>

Step 11:<br>
git checkout bug-fix<br>
git merge bug-fix-experimental<br>
manually resolved merge conflict inside STEPS.md<br>
git add STEPS.md<br>
git commit -m "Step 11."<br>
git push -u origin bug-fix<br>

Step 12:<br>
git add STEPS.md<br>
git commit -m "Step 12."<br>
git push -u origin bug-fix<br>