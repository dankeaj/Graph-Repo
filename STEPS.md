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
