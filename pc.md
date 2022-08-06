## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? 
    Git is a CLI, short for command line interface.
2. What is the difference between Git and GitHub?
    Git is a locally installed CLI, meanwhile GitHub is a GUI that hosts repositories for peoples projects and codes.
3. Why do we create a branch?
    We create a branch to make a copy of a repository, which allows you to mess with the code and stuff without affecting the original repository.
4. What is the purpose of a Pull Request?
    The purpose of a pull request is that it lets you tell other people about any changes youve pushed to a branch in a repository. 
5. What is the command you can use to switch between branches? For example you are working on the FIRSTNAME-LASTNAME branch and you want to switch back to main.
    The command you'd use to switch between branches is "git checkout" then the name of the branch to switch to.
6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do?
    Git fetch gets remote updates but doesnt merge the files, where as git pull does the same thing but merges the files. git merge combines multiples branches into the current branch.
7. What is a merge conflict?
    A merge conflict happens when git is trying to merge branches but the same part of the same file has changes, git doesnt know which to use, causing the conflict.
8. How do you resolve a merge conflict?
    To resolve a merge conflict, you have to pick which changed file you want to keep in the merge from which branch. Say, if you're merging a branch with the main branch and there are the same files but each are different, you have to pick if you want to keep the main branches file in the merge or the ladder.