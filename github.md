new Workflow


branching

main
----------------------------------
        \__________________/
          branch to do some work

How To Create a Branch

Checkout tells us to go to a different place
-b means to create a new branch
git checkout -b <name of your branch>

example: git checkout -b ds-first-branch

Git add and git  commit combined
git commit -am "updated a file"

To list all branches on local
hit Q when done viewing the branches
git branch

To push to a branch
git push origin <branch name>
   example:  cra-deploy git:(ds-first-branch) git push origin ds-first-branch

   git checkout <name of branch> without the b switch - allows you to look at a branch and literally check it out - view it

git checkout -  takes you to the last branch you were on

git pull origin main  
Do this after you merge on Github and before you add anything to your main branch