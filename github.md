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