## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
2. What is the difference between Git and GitHub?
3. Why do we create a branch?
4. What is the purpose of a Pull Request?
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
7. What is a merge conflict?
8. How do you resolve a merge conflict?

1. GIt is open-source version control system used to handle small to very large project efficiently
Used to tracking changes in the source code, enabling multiple developers to work toger on non-linear development.

2. Git is a version control system that lets you manage and keep track of your source code history. 
Github is a cloud-based hosting service that lets you manage Git repositories.

3. to isolate specific Git commits from the rest of your main Git history.

4. To let you tell others about changes you have pushed to a branch in a repository on Github.

5. git switch -c main

6. Git fetch updates you remote tracking branches under refs/remotes. This operation is safe to run at any time since it never changes any of you local branches. git merge is used to join two lines of history. If one of sides didn't do any work since last branching point (since merge base), the situation is either fast-forward (the branch you are on is simply updated to the tip of the branch you are merging), or up-to-date (there is nothing new to merge, and the branch you are on stays unchanged). 'git pull' is to update local project to remote so others can see what have you updated on the project.

7. An event that takes place when Git is unable to automatically resolve differences in code between two commits.

8.  https://www.rosipov.com/blog/use-vimdiff-as-git-mergetool/#fromHistor
