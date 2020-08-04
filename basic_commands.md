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
    <td>This config is only need for first time user.</td>
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

</table>

