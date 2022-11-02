## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git?
-an open source version control system (VCS) or another way to look at it would be a set of commands. Also according to their website it is "designed to handle everything from small to very large projects with speed and efficiency".

2. What is the difference between Git and GitHub?
-GitHub is a hub, wrapper, or cloud storage for Git Repositories (Folders with Code) while Git is a set of commands or an open-source version control system (VCS) used on the terminal; or for us pc users on GitBash because apparently our default terminal commands aren't great.

3. Why do we create a branch?
-Branches allow us to makes changes/alter (x)code without affecting the main branch of (x)code.

4. What is the purpose of a Pull Request?
-Pull request is a submission request to finalize the changes made on 1 branch of code and have it merge back with (x)Parent Branch. This request has a collaborative feature as well where multiple team members can see the changes and makes comments/suggestions.

5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
-There are 2 commands you can use. 
1 is the git checkout main command
2 is the git switch main command

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
git-fetch - Download objects and refs from another repository
git-merge - Join two or more development histories together. also:Incorporates changes from the named commits (since the time their histories diverged from the current branch) into the current branch.
git-pull - Fetch from and integrate with another repository or a local branch

7. What is a merge conflict?
-Merge conflicts occur when competing changes are made to the same line of a file, or when one person edits a file and another person deletes the same file.

8. How do you resolve a merge conflict?
-Brace yourselves, this is gonna be extensive: Here's how to deal with line change merge conflicts
    1. Open Git Bash.
    2. Navigate into the local Git repository that has the merge conflict.
    3. Generate a list of the files affected by the merge conflict. In this example, the file styleguide.md has a merge conflict.
    4. Open your favorite text editor, such as Visual Studio Code (my personal favorite), and navigate to the file that has merge conflicts.
    5. To see the beginning of the merge conflict in your file, search the file for the conflict marker <<<<<<<. When you open the file in your text editor, you'll see the changes from the HEAD or base branch after the line <<<<<<< HEAD. Next, you'll see =======, which divides your changes from the changes in the other branch, followed by >>>>>>> BRANCH-NAME. 
    6. Decide if you want to keep only your branch's changes, keep only the other branch's changes, or make a brand new change, which may incorporate changes from both branches. Delete the conflict markers <<<<<<<, =======, >>>>>>> and make the changes you want in the final merge. 
    7. Add or stage your changes.
    8. Commit your changes with a comment.

Now for the other type of merge conflict: Here's how to deal with removed file merge conflicts
    1. Open Git Bash.
    2. Navigate into the local Git repository that has the merge conflict.
    3. Generate a list of the files affected by the merge conflict. 
    4. Open your favorite text editor, such as Visual Studio Code, and navigate to the file that has merge conflicts.
    5. Decide if you want keep the removed file. You may want to view the latest changes made to the removed file in your text editor.
    6 Commit your changes with a comment.