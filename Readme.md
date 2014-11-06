Intro to Git and Github - Turing School 110414 
Rachel

This repository is the result of my work during that class

Some important commands:

$ git init								makes the cd a git repository
$ git status							summary of the repository status
$ git add filename.type					adds file in cd to staging area
$ git commit -m "add comment"			adds everything in staging area to repository
										best practice for comment: "verb (present tense) explain changes"
										ie "add second line"
$ git log
$ git commit .							DONT.  commits everything in the directory
$ git diff								shows changes
$ git diff filename.type				shows changes specific to file - Q to jump to prompt $
$ git reset HEAD filename.type			takes changes out of staging area