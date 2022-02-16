# Git-Cheat-Sheet

## This is a simple guide on how to use various git commands. 

***I will share with you both screenshots and codes for clarity.***

## 1. **Creating a repository.**

Let me take you through the steps for creating a new repository on github, if you have never used Command prompt to create a repository, this lesson might be what you need.

-The first command is the `git init` command. This will create a new git repository or convert a project you have been working on into a git repository. It initializes an empty repository.

-After creating a repository you will need a readme file, use `git add README.md` to create your readme.

-`git commit -m` command is what you will use next, this is to record all the changes you make in your repository. You can also add a simple message like this, `git commit -m "This is my initial commit" `

-`git branch -M main` This command changes the branch you are working on to the main branch in github

-Next you will create a new remote repo using the command `git remote add origin url`

-After creating the remote repo you will need to push changes into the repo, in which you will use the following command `git push <your_remote_name>`

-Alternatively, you can use the command `git push -u origin main` in this case git will, by default, choose your current branch as the branch to push to.

Here is a screenshot of what I have done on my command prompt to create the repository and the readme file you are currently reading;

![Screenshot (267)](https://user-images.githubusercontent.com/58620711/154179425-1d4e88ac-f844-4de5-8040-e9006e987e25.png)


##  2. **Common git commands**

Now that you can create a repository, add a readme file, make a commit and push, here are some git commnads that should be knowing as a developer.

These are commands that you will find yourself using almost everytime as you get more familiar with git and github.

- **Git Clone**   
If you love to work with other developers and copy some tips from them, git clone is definetely for you. It allows you to copy someone elses code to your own working space, and thereafter, you can make all the changes and modification you desire.
