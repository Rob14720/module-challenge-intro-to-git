## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
 Git is a software where coders work using an actual command line. It's an Open Source Distributed Version Control System.
 It is capable of actually modifying or adding files to the computer.
 Using its various functions you can write, save, and share code with your teammates,
or save it for your own personal projects by uploading it to GitHub by using push.

2. What is the difference between Git and GitHub?
 Git is the software where the coding happens. GitHub is the domain where it's accessible and is stored in a cloud.

3. Why do we create a branch?
  We create branches so that when we push our work to GitHub and look at the repository, you can compare your work
to the master file. This allows a review of your work before it's finally merged with the master (main) file.

4. What is the purpose of a Pull Request?
A pull request is to signal that you have done work and that you're asking for it to be merged with the main file.
You will most likely be pulling your branch that you named and worked in to Github to merge with the main file.
It will allow for anyone involved in the project to review your work for errors.
 
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
The "git checkout" command is how to switch between branches. the "git checkout -b (branch-name)" will create new branches.
To navigate branches that already exist you would simply command "git checkout (branch)" ex: 
"git checkout main" would get you back to the main branch.

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
They all move torwards the same thing. git fetch and git merge perform in two steps what git pull does in one.
Git fetch can be very effective in avoiding errors and merge conflicts as it shows you crucial information about changes
that have been made. After reviewing the etch you would git merge to perform the actual "pull".

7. What is a merge conflict?
A merge conflict is when something is odd about the pull. This would be like if another coder pull requested the same
files with similar changes that you just made. 

8. How do you resolve a merge conflict?
One way you could resolve a conflict would be to abort your current pull request which would reset everything to before
you made the request and then wait for the other coder to have their work reviewed/ merged instead.
