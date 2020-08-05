<h2>Push Project to Github (New User)</h2>

Follow the steps to Push/Upload our project to Github using Command line.


1. Create a new repository on GitHub. You can also add a gitignore file, a readme and a licence if you want

2. Open command prompt / Git Bash / terminal

3. Change the current directory to your local working project.

4. Set the author name and email address respectively which is needed for identifying your commits(useful when working in collaboration). This config is only needed for first time user. Note that this is not for logging into your github account.

		git config –global user.name "[name]" 
		git config –global user.email "[email address]" 

5. Initialize the local directory as a Git repository.

		git init

6. Add the files in your new local repository. This stages them for the first/initial commit.

		git add .

7. Commit the files that you’ve staged in your local repository with short message.

		git commit -m "initial commit"

8. Copy the https url of your newly created repository from Github

9. In the Command prompt, add the URL for the remote repository where your local repository will be pushed.

		git remote add origin URL_OF_REPO

10. Verifies the new remote URL

		git remote -v

11. Push the changes in your local repository to GitHub.

		git push origin master

12. For the First Time Users, It will ask for your Github username and password. This will be needed for first time only.

** Note : For Pushing any changes to the repo/project, you just need to follow step <b><i>5, 6 and 10.</b></i>**

That’s all

<br>

<p align="center">
    <img src="https://media.giphy.com/media/l9Jhzwdi09Ve0/giphy.gif" width="300">
    <br>
    Congratulation, Your First Local Repository pushed to GitHub.
</p>