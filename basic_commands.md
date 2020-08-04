<h2>
    Basic commands
</h2>

Open Terminal(Mac) or command prompt(Windows) and change directory to your project working directory.Then enter these commands :-

<br>

<table>
   <th>Git Command</th>
    <th>Description</th>
    <th>Recommendation</th>
    <th>Note</th>
  </tr>
  <tr>
    <td>

    git config –global user.name "[name]" 
    git config –global user.email "[email address]" 
    
</td>
    <td>This command sets the author name and email address respectively to be used with your commits.</td>
    <td>Highly Recommended</td>
    <td>This config is only needed for first time user.</td>
  </tr>

  <tr>
    <td>
    
     git init  
</td>
    <td>This Command will initialize the local Git Repository for your project.</td>
    <td>Highly Recommended</td>
    <td>This is the first command needed for every project.</td>
  </tr>

  <tr>
    <td>
    
     git clone [enter_git_repo_url_here]
</td>
    <td>This command is used to obtain a repository from an existing URL.</td>
    <td>Recommended</td>
    <td>This is used when we want a copy/clone of a project/repository on our machine</td>
  </tr>

  <tr>
    <td>
    
     git add [file_name]
</td>
    <td>This Command will add a file to index or staging area.</td>
    <td>Not Recommended</td>
    <td>This is used when we want a single file to be indexed</td>
  </tr>

  <tr>
    <td>
    
     git add .
</td>
    <td>This Command will add the entire directory recursively, including files whose names begin with a dot.</td>
    <td>Not Recommended</td>
    <td>This command stages all files including .files which we may or may not want to stage.</td>
  </tr>

  <tr>
    <td>
    
     git add *
</td>
    <td>This Command will  add all files in the current directory, except for files whose name begin with a dot.</td>
    <td>Highly Recommended</td>
    <td>This command stages all files excluding .files at one go</td>
  </tr>

  <tr>
    <td>
    
     git commit -m “[brief_message_about_this_commit]” 
</td>
    <td>This Command will commit the staged files.This command also takes a short/brief message about that particular commit</td>
    <td>Highly Recommended</td>
    <td>Meaningful commit message is recommended as it helps other developers/contributors/visitors to understand about that commit.</td>
  </tr>

  <tr>
    <td>
    
     git commit -a  
</td>
    <td>This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.</td>
    <td>Not Recommended</td>
    <td>This opens Shell, which might get overwhelming if you try to understand it now. To close Shell, enter Escape button on keyboard and then type ":q" then Enter.</td>
  </tr>

  <tr>
    <td>
    
     git status 
</td>
    <td>This Command will show you the status of the current working tree.</td>
    <td>Highly Recommended</td>
    <td>This command will help you at every stage. Alway check status before pushing the repository to the GitHub</td>
  </tr>

  <tr>
    <td>
    
     git diff 
</td>
    <td>This command shows the file differences which are not yet staged.</td>
    <td>Highly Recommended</td>
    <td>This command will help you identifying the difference by coloring the staged/not-staged lines with red and green and also with plus/minus symbols. When you are done, you can press the "q" or ":q" key to quit.</td>
  </tr>

  <tr>
    <td>
    
    git diff –staged  
</td>
    <td>This command shows the differences between the files in the staging area and the latest version present.</td>
    <td>Recommended</td>
    <td>This command will help you identifying the difference by color red and green and also with plus/minus symbols. When you are done, you can press the "q" or ":q" key to quit.</td>
  </tr>

  <tr>
    <td>
    
    git diff [first_branch_name] [second_branch_name]  
</td>
    <td>This command shows the differences between the two branches mentioned.</td>
    <td>Recommended</td>
    <td>This command will help you identifying the difference by color red and green and also with plus/minus symbols. When you are done, you can press the "q" or ":q" key to quit.</td>
  </tr>

  <tr>
    <td>
    
    git reset [file_name] 
</td>
    <td>This command unstages the file, but it preserves the file contents.</td>
    <td>Recommended</td>
    <td>This command will remove the particular file from stage area.</td>
  </tr>

  <tr>
    <td>
    
    git reset [commit_id] 
</td>
    <td>This command undoes all the commits after the specified commit and preserves the changes locally.</td>
    <td>Recommended</td>
    <td>Use this command if you know what you are doing. check status of the changes to keep track.</td>
  </tr>

  <tr>
    <td>
    
    git reset –hard [commit_id]
</td>
    <td>This command discards all history and goes back to the specified commit.</td>
    <td>Recommended</td>
    <td>Use this command if you know what you are doing. check status of the changes to keep track.</td>
  </tr>

  <tr>
    <td>
    
    git rm [file_name]
</td>
    <td>This command deletes the file from your working directory and stages the deletion.</td>
    <td>Recommended</td>
    <td>Use this command if you know what you are doing.Check twice which file you are about to delete. Check status of the changes to keep track.</td>
  </tr>

  <tr>
    <td>
    
    git log
</td>
    <td>This command is used to list the version history for the current branch</td>
    <td>Highly Recommended</td>
    <td>Also Check status of the changes to keep track.</td>
  </tr>

  <tr>
    <td>
    
    git log –follow[file_name]
</td>
    <td>This command lists version history for a file, including the renaming of files also.</td>
    <td>Highly Recommended</td>
    <td>Also Check status of the changes to keep track.</td>
  </tr>

  <tr>
    <td>
    
    git show [commit_id]
</td>
    <td>This command shows the metadata and content changes of the specified commit.</td>
    <td>Highly Recommended</td>
    <td>Also Check status of the changes to keep track.</td>
  </tr>

  <tr>
    <td>
    
    git tag [commit_id]
</td>
    <td>This command is used to give tags to the specified commit.</td>
    <td>Recommended</td>
    <td>A lightweight tag is very much like a branch that doesn't change — it's just a pointer to a specific commit.</td>
  </tr>

  <tr>
    <td>
    
    git branch
</td>
    <td>This command lists all the local branches in the current repository.</td>
    <td>Highly Recommended</td>
    <td>useful when working in a team</td>
  </tr>

  <tr>
    <td>
    
    git branch [new_branch_name]
</td>
    <td>This command creates a new branch.</td>
    <td>Highly Recommended</td>
    <td>Alway create a branch if you are not sure about feature you are about to add.</td>
  </tr>

  <tr>
    <td>
    
    git branch -d [branch_name] 
</td>
    <td>This command deletes the particular branch.</td>
    <td>Highly Recommended</td>
    <td>Delete branch when you have merge the feature with the master branch</td>
  </tr>

  <tr>
    <td>
    
    git checkout [branch_name]   
</td>
    <td>This command is used to switch from one branch to another.</td>
    <td>Highly Recommended</td>
    <td>Branching the project feature and the merging it,  is very helpful.</td>
  </tr>

  <tr>
    <td>
    
    git checkout -b [branch_name]    
</td>
    <td>This command creates a new branch and also switches to it.</td>
    <td>Highly Recommended</td>
    <td>Branching the project feature and the merging it,  is very helpful.</td>
  </tr>

  <tr>
    <td>
    
    git merge [branch_name]      
</td>
    <td>This command merges the specified branch’s history into the current branch.</td>
    <td>Highly Recommended</td>
    <td>Branching the project feature and the merging it,  is very helpful.</td>
  </tr>

  <tr>
    <td>
    
    git remote add [variable_name] [Remote_Server_Link]   
</td>
    <td>This command is used to connect your local repository to the remote server.</td>
    <td>Highly Recommended</td>
    <td>Default Remote is "origin" but you can change as per your preference</td>
  </tr>

  <tr>
    <td>
    
    git push [variable name] master  
</td>
    <td>This command sends the committed changes of master branch to your remote repository.</td>
    <td>Highly Recommended</td>
    <td>Default Remote is "origin" and default master branch_name is "master" but you can change as per your preference</td>
  </tr>

  <tr>
    <td>
    
    git push [variable name] [branch]    
</td>
    <td>This command sends the branch commits to your remote repository.</td>
    <td>Highly Recommended</td>
    <td>Default Remote is "origin" and default master branch_name is "master" but you can change as per your preference</td>
  </tr>

  <tr>
    <td>
    
    git push –all [variable name]    
</td>
    <td>This command pushes all branches to your remote repository.</td>
    <td>Highly Recommended</td>
    <td>Pushes all new updates to the server's repo.</td>
  </tr>

  <tr>
    <td>
    
    git push [variable name] :[branch name]  
</td>
    <td>This command deletes a branch on your remote repository.</td>
    <td>Recommended</td>
    <td>Use this command if you know what you are doing.Check twice which file you are about to delete. Check status of the changes to keep track.</td>
  </tr>

  <tr>
    <td>
    
    git pull [Repository_Link]  
</td>
    <td>This command fetches and merges changes on the remote server to your working directory.</td>
    <td>Recommended</td>
    <td>Basically updates and merges the changes on your local repo </td>
  </tr>

</table>


<p align="center">
    <img src="https://media.giphy.com/media/EtB1yylKGGAUg/giphy.gif" width="300">
    <br>
    Don't be frustrated with all this commands. <br>The best way to learn, is to make lots of mistakes.
</p>

