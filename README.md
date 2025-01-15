[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=17724611)
# Sp25Lab1

Lab 1 for Spring 25 Data Structures

## Using VS Code for an assignment

### Overview of the process we will use

All labs this semester will be made available as git repo stored on GitHub. In order to complete the labs this semester on your local machine you will need to:

1.  _Clone the lab repo_: Cloning is the process of making a local copy of the lab's GitHub repo.
2.  _Editing/Doing the Lab_: Editing of the starter code for a lab or creating new Python files for a lab is done using your local VS Code software.
3.  _Committing & Pushing_: (I know the terminology is weird but I did not make it up!) Committing (officially a Commit) is the process of saving the changes made to the repo you cloned to your local repo. Pushing (officially a Push) is the process of saving the changes you have made to your lab's repo on GitHub. They are always done in that order: commit first then push second.

### Cloning a lab repo from GitHub

The first step in cloning the lab repo from GitHub is to copy the url of the repo. The following image illustrates the two steps in this process.

![Get the repo url ](images/CloningRepo.png)

The second step is to make a copy of the repo on your local machine. We will use VS Code to clone the repo. Your VS Code should open to the Welcome page, which you can see in the background of the following image. Click the _Clone Git Repository_ link and you will see the dialog box shown in the foreground of the image. Click in the top box and paste in the url of your lab GitHub repo. (You copied it in the step above.)

![Make a local copy of the repo](images/Cloning-a-repo.png)

After you click the link in the blue font or press the enter (return) key your file explorer will open up asking where you want to save the repo. _Save it somewhere you will remember._ You will have to find it again.

### Using VS Code

_Cloning vs Opening_: The following diagram displays the Welcome page for VS Code. The preceding section discussed the use of the _Clone Git Repository_ command. You use it to make the initial copy of a GitHub repository on your local machine. The _Open_ command is used to open a git repository at all other times. Note that git repositories are stored on your computer as a folder. So you use the _Open_ command to open a folder. **Always open a folder in VS Code, not a file!**

![Clone vs Open](images/VSCode-Welcome.png)

_Navigating in VS Code_: An open repo in VS Code will appear similar to the following diagram. The Welcome tab can be closed by clicking the close icon. the X, in the tab. A file can be opened by clicking the name of the file in the left hand menu drawer. Note that you have to click the workspace icon in order to see the file and sub-folder content of the repo. In the case of the diagram, the HelloWorld.py file has been clicked once to display the file's contents in an editor tab.

![Navigating VS Code](images/NavigatingVSCode.png)

The buttons in the left-most drawer are used to navigate within the functions that VS Code supplies. As the semester progresses you will learn to use most of these buttons.

_Note_: In git terminology, the folder that contains the files of the repo is known as the workspace.

_Editing & Running a Program_ Editing a program involves: (1) clicking on the name of the program file to open the editor tab, (2) editing the program by typing in the editor, and (3) saving the file (command-s on Mac computers and control-s on Windows). To run (execute) a program you right click on the name of the file to open the file's context menu and select Run Python File in Terminal. The following image illustrates the context menu for running a program.

![Running a Program](images/Running-a-program.png)

The output for a program is shown in the following image.

![Program Execution](images/ProgramExecution.png)

### Saving changes to local and remote repos

_Overview_: There are three steps that are required to save the changes you make to your repo. Actually, you have two repos: a local repo, and a remote repo. Keeping both these repos in sync with the changes to your project is your responsibility. Nothing happens automatically with git.

The two steps required to save your project to your local repo are:

1.  Stage all changes. (#3 in the following image)
2.  Commit your changes to your local repo. There are two steps to this process:
    1.  Write a short Commit message to indicate the changes. (50 characters max)
    2.  Check the Commit button and wait until the timer on the GIT icon goes away.

![Staging and Committing your local repo](images/Git-1.png)

The final step in syncing your local work with your GitHub repo (your remote repo) is to push the commit back to the remote repo. The git command for doing this is called push and the following image shows you what you will see in VS Code.

![Pushing Commits back to the remote repo](images/Git-2.png)

Like a commit, you will see a timer icon as a badge to the git icon in the left most drawer. Wait until the timer goes away, then check your GitHub repo to see if your changes were pushed. A quick way to tell this is to look at the file changed and see if your commit message is listed. Of course, you can always open the file and check its content. You may have to refresh your browser window to see the new commit.
