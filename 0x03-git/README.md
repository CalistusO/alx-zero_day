Alx Tasks For Git

Task 0:

Create and setup your Git and GitHub account

Task 1:

Create a new directory called 0x03-git in your alx-zero_day repo.
Make sure you include a not empty README.md in your directory.

Task 2:

A. Create these directories at the root of your project: bash, c, js
B. Create these empty files:
c/c_is_fun.c
js/main.js
js/index.js
C. Create a file bash/alx with these two lines inside: 
i. #!/bin/bash
ii. echo "ALX"
D. Create a file bash/school with these two lines inside: 
i. #!/bin/bash
ii. echo "School"
E. Add all these new files to git
F. Commit your changes (message: "Starting to code today, so cool") and push to the remote server

Task 3:

For this project, create a branch update_script and in this branch:
A. Create an empty file named bash/98
B. Update bash/alx by replacing echo "ALX" with echo "ALX School"
C. Update bash/school by replacing echo "School" with echo "The school is open!"
D. Add and commit these changes (message: "My personal work")
E. Push this new branch
Ho wait, your manager needs a quick fix in your project and it needs to be deployed now:
A. Change branch to main
B. Update the file bash/alx by replacing echo "ALX" with echo "ALX School is so cool!"
C. Delete the directory js
D. Commit your changes (message: "Hot fix") and push to the origin

Task 4:

For this task -and only for this task- please update your file README.md in the main branch from GitHub.com. It is the only time you are allowed to update and commit from GitHub interface.
After you have done that, in your terminal:
A. Get all changes of the main branch locally (i.e. your README.md file will be updated)
B. Create a new file up_to_date at the root of your directory and in it, write the git command line used
C. Add up_to_date to git, commit (message: "How to be up to date in git"), and push to the origin

Task 5:

Merge the branch update_script to main.
HHHHHHHAAAAAAAA
CONFLICT (content): Merge conflict in bash/alx
As you can see, you have conflicts between two branches on the same file.
Your goal now is to resolve conflicts by using the version of the branch update_script, and push the result to the origin.

Task 6:

Create a .gitignore file and define a rule to never push ~ files.
