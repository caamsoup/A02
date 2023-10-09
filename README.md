# A02

# Webstorm Tutorial
Webstorm is a IDE created by JetBrains used mainly to program in JavaScript but can also be used to program websites and in web programming languages

How to set up Webstorm
     - Download Webstorm from the JetBrains site
        - https://www.jetbrains.com/community/education/#students 
     - Run the downloading process
     - Wait for the process to finish
     - Open Webstorm
     - On the Welcome screen, you should see a "New Project" button with a plus sign symbol, click on that to open a new file
        - If you want to open a previous code file, click "Open" with a folder icon
     - After you create a new project, you should see the project tool window, click on "New" in order to create a html, style sheet, or javascript file (or other file types)
     - When you are done writing your code and want to test it, on the right hand side, there should be a browser button, click it to view your webpage in said browser

# Connecting Git
Github is an open source version control system, which means it keeps track of changes in your source code. The best part of this is that it can **merge** back to a previous code version if an unfixable-bug occurs

Setting up **Git** with Webstorm
     - Download Git
       - https://git-scm.com/downloads
     - Create a **Github** account
       - https://github.com/join
     - Go into Webstorm, click (Ctrl + Alt + S) to access system settings
     - Under Version control Git, enter the path to your git.exe
     - Now go to "Appearance and Behavior" then "System Settings" then "Passwords", and add a location for the password file
        - It will **fetch** the information
     - Go back into Github, click the plus sign in the corner and "New **repository**"
       - Make sure to make the repository public and add a readme file, then click "Create"
     - Go back into Webstorm and on your open project, select VCS in the menu at the top
     - Import the repository into Version Control 
     - Enter Github repository name and local path name, as well as a **branch** name 
     - Open the Add to Git dialog option and click add
     
Commiting files to Github
     - Add a message to the commit message area
     - Select which files you want to commit
     - Click commit or **push**

**Pulling** code from Github
     - If you want to get previous code from Github that you have written, click on master or whatever your branch is named
     - Then, click on "Update Project" and either one of the options
     

What if I cannot merge or commit?
     - If you are having a **merge conflict**, just change the code until it can **merge**, and then commit again
     - Usually the merge conflict is due to 2 seperate people trying to merge or because the code is incorrect

**Cloning** a repository
According to Github, "When you create a repository on GitHub.com, it exists as a **remote** repository. You can clone your repository to create a local copy on your computer and sync between the two locations."
     - In order to clone your online repository, you must first go to the main page of your repository
     - Click on the "<> Code" green button
     - Copy the URL for the repository in HTTPS
     - Go back into Webstorm, and link the repository to the project

# Glossary 
     - Branch: The area where your code will be placed into. There can be multiple branches
     - Clone: Creating a double for local use
     - Commit: Sending your code to your repository
     - Fetch: Get the information from the software
     - GIT: Software that tracks any changes made to the code that you wrote, and allows for collaboration
     - Github: Online version of Git, can store changes on their cloud instead of just locally
     - Merge: Making two different codes come together
     - Merge Conflict: When the code cannot come together due to a problem with it
     - Push: Send the code to Git and Github repositories
     - Pull: 
     - Remote
     - Repository
