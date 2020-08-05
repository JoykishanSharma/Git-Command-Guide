<h2>Push Project to Github (Old User)</h2>

Follow the steps to Push/Upload our project to Github using Command line.


1. Create a new repository on GitHub. You can also add a gitignore file, a readme and a licence if you want

2. Open command prompt / Git Bash / terminal

3. Change the current directory to your local working project.

4. Initialize the local directory as a Git repository.

		git init

5. Add the files in your new local repository. This stages them for the first/initial commit.

		git add .

6. Commit the files that you’ve staged in your local repository with short message.

		git commit -m "initial commit"

7. Copy the https url of your newly created repository from Github

8. In the Command prompt, add the URL for the remote repository where your local repository will be pushed.

		git remote add origin URL_OF_REPO

9. Verifies the new remote URL

		git remote -v

10. Push the changes in your local repository to GitHub.

		git push origin master

** Note : For Pushing any changes to the repo/project, you just need to follow step <b><i>5, 6 and 10.</b></i>**

That’s all

<br>

<p align="center">
    <img src="https://media.giphy.com/media/3XEgV9kfwLy1i/giphy.gif" width="300">
    <br>
    Finally Local Repository pushed to GitHub.
</p>