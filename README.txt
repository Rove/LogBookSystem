STEPS | STEPS | STEPS | STEPS | STEPS | STEPS | STEPS
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
Open git-bash

Acer@ACER-PC / <master>
$ git init

Acer@ACER-PC / <master>
$ git config --global user.name "Rove"

Acer@ACER-PC / <master>
$ git config --global user.name "rmayungon@apc.edu.ph"

Acer@ACER-PC / <master>
$ git clone git@github.com:Rove/LogBookSystem.git

Acer@Acer-PC / <master>
$ cd LogBookSystem

Acer@ACER-PC /LogBookSystem <master>
$ git init

Acer@ACER-PC /LogBookSystem <master>
$ git config --global user.name "Rove"

Acer@ACER-PC /LogBookSystem <master>
$ git config --global user.name "rmayungon@apc.edu.ph"

Acer@ACER-PC /LogBookSystem <master>
$ git remote add upstream git://github.com/yourusername/LogBookSystem.git

Acer@ACER-PC /LogBookSystem <master>
$ git fetch upstream

+++++++++++++++++++++++++++++++++++++++++
Start adding something to the ProjectPlanFinal.doc
+++++++++++++++++++++++++++++++++++++++++

Acer@ACER-PC /LogBookSystem <master>
$ git add ProjectPlanFinal.doc

Acer@ACER-PC /LogBookSystem <master>
$ git commit -m 'comment kung ano dinagdag mo'

Acer@ACER-PC /LogBookSystem <master>
$ git remote add origin git@github.com:Rove/LogBookSystem.git

Acer@ACER-PC /LogBookSystem <master>
$ git push origin master

+++++++++++++++++++++++++++++++++++++++++
Start adding again something to the ProjectPlanFinal.doc
+++++++++++++++++++++++++++++++++++++++++

Acer@ACER-PC /LogBookSystem <master>
$ git pull upstream master

Acer@ACER-PC /LogBookSystem <master>
$ git add ProjectPlanFinal.doc

Acer@ACER-PC /LogBookSystem <master>
$ git commit -m 'comment kung ano dinagdag mo'

Acer@ACER-PC /LogBookSystem <master>
$ git push origin master



=======================================================================
NEED TO DO TIME TO TIME ESP. WHEN YOU'RE ABOUT TO PUSH YOUR WORK
=======================================================================
Pulling upstream changes:
(Some time has passed, the upstream repo has changed and you want to update your fork before you submit a new patch.)
+ git fetch upstream
+ git merge upstream/master
or
+ git pull upstream master