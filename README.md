# Welcome to the learning github repository !

- If you are an absolute newbie to git and github this is the place for you.
- Here i have documented the learnings and steps i took to learn all about this version control system.
- Feel free to diverge from my path wherever necessary if it doesnt match your use needs.

## What exactly is Git

- Git is a free and open source version control system.
- It is a tool used to track changes made in your code.

## What is version control

- In simple words version control is a way for programmers to track code changes.
- You start by saving an initial version of your code into git , as you continue to change your code you keep saving over the initial version and creating newer versions.
- This helps us keep track of the changes we make,find bugs and go back to previous versions of code if required.

## What is Github

- Github is an online platform(Website) which shows all the code and changes to code which you saved on git .
- Being an online forum it also enables you to work with others and access their code.It also allows others to acces and change your code.
- It allows you to put all of the code for your project into a single folder(also called REPOSITORY) and make it available for potential employers.

## Still unclear about the difference between git and github ?

- Here is a link which helped me out : https://blog.devmountain.com/git-vs-github-whats-the-difference/

## Step1 : Download Visual Studio Code

- Go to https://code.visualstudio.com/ .
- Go to https://www.youtube.com/ and search "How to download VS code".
- Follow along with any one video and download VS code.

### What is Visual Studio Code

- Visual Studio Code or VS Code for short is a code editor.

### What is a code editor ?

- Code can be typed out anywhere.Be it in a notepad file or in a word document.But both Notepad and Microsoft Word are unable to understand that what is being typed is code so the process becomes tedious.This is where code editors come in.
- There are certain apps which work just like notepad but are able to detect the code you type and format it into a neat and readable form.They also have additional features like autocomplete,auto format,user snippets and many others.
- VS Code is one such application.

## Step2 : Download Git
- Go to https://git-scm.com/
- Click on downloads the installer will be downloaded to your system.
- Run the installer and foloow the on screen instructions to install git on your system.If you are a complete beginner like i was then there is no need to change any of the options in the installer.Default options are more than enough.

## Step3 : Create a github account
- go to https://github.com/
- click sign up and create an account on github.

## Step4 : Open git bash
- git bash can be opened by pressing the windows key and searching 'git bash'.
### What is git bash
- It is a command-line shell for enabling git with the command line in your system.
### What is a shell ? 
- A shell is used to interface with an operating system through written commands.
- Different applications have their own built in command line shells.
- Windows also has its own command line shell called command prompt.
![image](https://user-images.githubusercontent.com/85004364/124898133-891c0680-dffc-11eb-9236-ab082d916603.png)

## Step5 : A few initial config commands(To be typed in git bash shell)
- Dont forget to press enter key to run each command after typing it out
### Configuring username and email
- git config --global user.name "type your github username here".
- git config --global user.email "type the email you used in your github account".
### Setting up an SSH key on github
- go to https://www.youtube.com/watch?v=WgZIv5HI44o
- One thing i want to mention was in my system the .ssh folder was in C:\Users\'your username'\AppData\Roaming\SPB_Data so you may need to use that path when trying to copy to clipboard
#### What is an SSH key
- An SSH key as i understood it is basically a layer of security added to link your git and github.
- The way i understand SSH is it is a pair of files.For example , if i create an ssh key with the file name "hello" ,2 files are actually generated. hello and hello.pub
- Both hello and hello.pub have a unique serial number but what links the 2 is that you can generate hello.pub 's serial number only using that of hello .
- What we do is add hello.pub to our github account and keep hello so that when we try to take code from github or add code to it , the operations will work only if we have hello on our system.
- This prevents others from modifying our code.

## step6 : Now you are all set to learn git and github
- Here is a wonderful youtube video i used to get the basics down https://www.youtube.com/watch?v=RGOj5yH7evk&t=1361s
- Check the comments of the video if you have any doubts. This helped me a lot.

