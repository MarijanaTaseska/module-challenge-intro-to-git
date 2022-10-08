## Research Questions 

Now that you are all set up, it's time to learn a little more about the tools of the trade. Edit this file and answer the following questions. You are going to need to start familiarizing yourself with the [GitHub docs](https://docs.github.com/en). Docs (short for documentation) are the instructions on how to use a languge or program. A large part of your job as a developer will be learning how to read and work with documentation. Please reference the GitHub docs when answering the questions below. If you cannot find what you are looking for in the docs, you can always start to practice your Google skills!

1. What is Git? 
- Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and effeciency. It will allow us to store our code safely in the cloud, keep track of changes to our code over time, and allow us for quick and easy collaboration with other developers.

2 What is the difference between Git and GitHub? 
-Git is the actual command that we are running in the terminal, its a version control system that lets you manage and keep track of your source code history. GitHub is a cloud based hosting service that lets you manage Git repositories.

3. Why do we create a branch? 
-Branching allows more developers to work on same project withouth causing traffic jam. It allows us to make a copy of the initial code and making changes to it without changing the original code and then pushing back into the main code after making the changes so it is available to everybody. 

4. What is the purpose of a Pull Request? 
- Pull request is a feature in GutHub that offers an easy, web-based way to submit your work.

5. What is the command you can use to switch between branches? For example you are working on FIRSTNAME-LASTNAME branch and you want to switch back to main. 
- git switch <main>

6. Explain the difference between `git fetch`, `git merge` and `git pull`. What does each command do? 
  - 'git fetch' is a primary command used to download contents from aremote repository. 'git merge' lets you take the independent lines of development created by git branch and integrate them into a single branch. 'git pull' is used to fetch and download content from a remote repository and immediately update the local repository to match that content.

  7. What is a merge conflict? 
  - Merge conflict happen when you merge branches that have competing commits and Git needs your help to decide which changes to incorporate in to the final merge.

  8. How do you resolve a merge conflict? -Under repository name click 'Pull request'. Under 'Pull request' click the pull request with a merge conflict that you'd like to resolve. Near the bottom of the pull request, click Resolve conflicts. Decide what branch's changes you want to keep.Delete the conflict markers <<<<<<, ======< >>>>>>. and make the changes you want in your final merge.
