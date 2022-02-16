# Git-Cheat-Sheet

## This is a simple guide on how to use various git commands. 

***I will share with you both screenshots and codes for clarity.***

## 1. **Creating a repository.**

Let me take you through the steps for creating a new repository on github, if you have never used Command prompt to create a repository, this lesson might be what you need.

- The first command is the `git init` command. This will create a new git repository or convert a project you have been working on into a git repository. It initializes an empty repository.

- After creating a repository you will need a readme file, use `git add README.md` to create your readme.

- `git commit -m` command is what you will use next, this is to record all the changes you make in your repository. You can also add a simple message like this, `git commit -m "This is my initial commit" `

- `git branch -M main` This command changes the branch you are working on to the main branch in github

- Next you will create a new remote repo using the command `git remote add origin url`

- After creating the remote repo you will need to push changes into the repo, in which you will use the following command `git push <your_remote_name>`

- Alternatively, you can use the command `git push -u origin main` in this case git will, by default, choose your current branch as the branch to push to.

Here is a screenshot of what I have done on my command prompt to create the repository and the readme file you are currently reading;

![Screenshot (267)](https://user-images.githubusercontent.com/58620711/154179425-1d4e88ac-f844-4de5-8040-e9006e987e25.png)


##  2. **Common Git commands**

Now that you can create a repository, add a readme file, make a commit and push, here are some git commnads that should be knowing as a developer.

These are commands that you will find yourself using almost everytime as you get more familiar with git and github.

- **Git Clone**   
If you love to work with other developers and copy some tips from them, git clone is definetely for you. It allows you to copy someone elses code to your own working space, and thereafter, you can make all the changes and modification you desire. Here is are two screenshots of how i have done it; in the first screenshot, i have copied the link, in the second screenshot, I have written the command in my command prompt


![Screenshot (279)](https://user-images.githubusercontent.com/58620711/154206843-dde98044-535f-48cd-903b-e882c0913364.png)


![Screenshot (276)](https://user-images.githubusercontent.com/58620711/154206907-d021a26c-3c1a-4cb6-8c50-a75916f36cf4.png)

- **Git Checkout**
 
 At some point you will need to switch from one branch to another, to do so use the command `git checkout <name-of-your-branch>`
 
 However, do not just switch branches without making sure that you have made commit on the branch you were working on.
 
 - **Git Status**

 This command will give you all the details about the branch you are in. 
 
 I have written the commnad and this is the current information of the branch I am at. Try it on your machine.
 
 ![Screenshot (285)](https://user-images.githubusercontent.com/58620711/154209390-b2e4bec1-9981-4ef6-9ef8-d0898238a0ec.png)
 
 - **Git add**





 
