# lia-made-a-repo
 03/23/20 DPG Git Tutorial

Hi, let's get started.
Follow
https://help.github.com/en/desktop/getting-started-with-github-desktop/creating-your-first-repository-using-github-desktop
alongside the additional/modified instructions below.

Step 1. Install and sign into GitHub Desktop
- message Lia on slack your GitHub username

Step 2. Create a new repository
- give it whatever Name and Description you want
- make an empty folder on your computer, not on Dropbox
- when you Create a New Repository, make this folder the Local Path
- check "Initialize this repository with a README"
- Git ignore: None.  Later, we will add the file extensions of our data files so that Git will ignore them.
- License: GNU GPLv3.  Always specify a license; if you don't, it's actually not open-source because outsiders cannot use your code legally

Read Step 3

Step 4. Push your repository to GitHub
- After clicking Publish repository, make sure "Keep this code private" is unchecked so we know when we all got the hang of it
- Organization: None.  For future, non-tutorial repositories, we'll want to set Organization to Dave-Patterson-Group
- Following substep 3, you should now be able to view your repository on your GitHub account online

Skip Step 5 because we're using Matlab, not a text editor

Do Step 6.
- Substep 1: Instead of "Open in EDITOR", click Repository > Show in Explorer, and edit in Notepad or some other text editor, to change the README.md file
- Follow the rest of Step 6.  When you view your repository online at the end, the text in your README.md file should be the text at the bottom of the landing page of your online repository

Our Step 7. Add, commit, and push a Matlab code file.
Make a Matlab code file and make its location inside the folder of your local machine where your repository is.  GitHub Desktop will automatically update so you can see the new file in the Changes tab of your Current repository.
Repeat what you did in Step 6 to "Commit to master" and "Push origin".

Our Step 8.
Open Repository > Repository settings > Ignored files.
Following https://guide.freecodecamp.org/git/gitignore/, add the 2 lines
*.csv
*.fig
to the box and click Save.  This will make git ignore all files with file extension csv (such as our spectra) and all Matlab figures.  For your future git repositories, list all your non-code file extensions and specific files here.

We're done!  Send Lia a Slack message to celebrate your victory.