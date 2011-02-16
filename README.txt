Downloading the repository in your local computer:
+ Fork
+ Open git-bash
+ git clone git@github.com:Rove/LogBookSystem.git
+ cd LogBookSystem
+ git remote add upstream git://github.com/____/LogBookSystem.git
   - e.g. git remote add upstream git://github.com/Rove/LogBookSystem.git
+ git fetch upstream
+ Start editing the ProjectPlan
------------------------------------------------------------------------------------
Commiting your work to the repository: (open git-bash)
+ git add ProjectPlan
+ git commit -m 'comment of what you've done'
   - e.g. git commit -m 'added info to 1.1 Purpose, Scope, and Objectives'
+ git remote add origin git@github.com:Rove/LogBookSystem.git
+ git push origin master
------------------------------------------------------------------------------------
Pulling upstream changes:
(Some time has passed, the upstream repo has changed and you want to update your fork before you submit a new patch.)
+ git fetch upstream
+ git merge upstream/master
or
+ git pull upstream master