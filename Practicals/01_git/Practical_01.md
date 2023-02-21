# Git

## Basic usage and setup

1. What is Git and why we use it?
   - https://en.wikipedia.org/wiki/Git
   - Version control, collaboration (branches), backup
2. GitHub repository for this course
   - https://github.com/wenceslasdk/data-science-2
   - All students create a GitHub account
3. Git client with a nice GUI
   - https://www.sourcetreeapp.com/
   - Download and install Sourcetree 
   - Need to install Git, Mercurial is not needed
   - Add account into Sourcetree 
     - Tools -> Options -> Authentication -> Add
     - Select Github, click “Refresh OAuth Token” -> log in -> Authorize
4. Creating a fork of the repository
   - https://docs.github.com/en/get-started/quickstart/fork-a-repo
   - Add repository to Sourcetree
     - Remote -> GitHub account -> data-science-2 -> clone
     - Choose location -> clone
5. Keeping the fork updated
   - https://docs.github.com/en/github/collaborating-with-pull-requests/working-with-forks/syncing-a-fork
   - web UI “Fetch and Merge”
   - other option (“Configure a remote for a fork” using “Terminal” (git remote add upstream https://github.com/wenceslasdk/data-science-2.git), pull from upstream)
6.	Create a branch


## Practical examples
1. Update changes from the upstream
   - Teacher to fill in the lines below, commit and push the changes

         Number of students present: who knows
         Weather outside: dark, cannot see
   
   - Students pull the changes
   - Merge into your branch

2. Make changes in your own repository 
   - Students to fill the lines below, commit and push the changes
   
         Year of study:
         Number of lectures today:

# Prerequisites for the following practicals 

In the remaining time or as homework until the next practical, download and install:
- PyCharm
  - https://www.jetbrains.com/pycharm/
  - IDE (Integrated Development Environment) for Python
- Anaconda
  - https://www.anaconda.com/
  - This will allow us to use Jupyter notebooks
- install nbextentions
  - https://jupyter-contrib-nbextensions.readthedocs.io/en/latest/install.html
  - this adds table of contents to Jupyter notebooks
