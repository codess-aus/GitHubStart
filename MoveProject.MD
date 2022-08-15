

Having a project already stored locally enables you to move it to GitHub rather quickly. The following activity provides instructions to move your local project to GitHub using various tools. Select the tool you are most comfortable with and get importing 😄.

Moving your local project:
In the Code tab of this repository, copy the URL shown under Quick Setup.
Follow the instructions below based on what tool you'd like to use locally.
Using the command line
Using the command line
In your command line, navigate to your project directory. Type git init to initialize the directory as a Git repository.
Type git remote add origin https://github.com/codess-aus/github-upload.git
Type git add .
Type git commit -m "initializing repository"
Type git push -u origin main to push the files you have locally to the remote on GitHub. (You may be asked to log in.)
Note: You can also use a password protected SSH key to connect to GitHub. See Connecting to GitHub with SSH in our documentation to learn more.

Using GitHub Desktop
Using GitHub Desktop
GitHub Desktop doesn't allow you to add a new remote for an existing directory, so instead we'll copy the contents of your existing folder to our repo. If you'd like to keep your existing folder, you may want to use the command line or one of the other tools.

In GitHub Desktop, click on File and Clone a repository.
Click on the URL tab.
Paste the URL from this repository.
Move the contents of your local repository to this directory.
Create a commit by entering a commit message and then clicking on Commit to main
Click Publish branch in the top right corner to push your repository to GitHub.
Using Visual Studio Code
Using Visual Studio Code
In Visual Studio Code, open the folder for your project.
Click the icon on the left for Source Control.
On the top of the Source Control panel, click the Git icon.
If the files you see match the repository you want to create, click Initialize Repository.
Next to the word CHANGES, click the symbol of the plus sign to stage all of the changes.
This is part of the two stage commit. You can use this staging function to create meaningful commits throughout the development process.
In the box in the Source Control panel, type a commit message. Something like "initial commit - moving project" could work.
Click the checkmark at the top of the Source Control panel.
Open the integrated terminal found under View > Integrated Terminal.
In your command line, type git remote add origin https://github.com/codess-aus/github-upload
In the Source Control Panel, click the expandable three dots that open a menu of options.
When asked if you'd like to publish the branch, click Okay.
