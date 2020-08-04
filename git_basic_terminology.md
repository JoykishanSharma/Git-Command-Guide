<h2>Git Basic Terminology</h2>

Before using the git command we need to understand these terminologies, which we will be using very frequently in the git commands and also in the description. It is important to have the understanding of these terms or you might have rough time implementing the git commands. Besides its great to know these terms, it will make your learning process fast.

<br>

<table>
    <th>Git Term</th>
    <th>Description</th>
    <tr>
        <td>Repository or "Repo"</td>
        <td>This is a local place on your machine where the entire snapshot of your project is stored. Every minor/major change is stored here and can be retrieved. Repository logs can easily be viewed and retrieved, i.e, you can time-travel inside your project.</td>
    </tr>
    <tr>
        <td>Index (Staging area, Cache)</td>
        <td>An Index is the snapshot of your next commit. It is where the code moves to, once you stage or add (git add) the code in the Working directory. A Staging area is like a cache memory and acts as a middle layer between the working directory (where the code is developed) and the local repository (where the code resides).</td>
    </tr>
    <tr>
        <td>Commit</td>
        <td>A commit is the latest snapshot (state) of a project. Every commit has a unique commit ID. All commit logs are stored in the local repository. A commit is a git object that stores the following attributes: commit ID, author name, authored date, and a commit message (header and body).</td>
    </tr>
    <tr>
        <td>Branch</td>
        <td>A branch is a parallel, independent line of development. A branch lets you work on the same piece of code in your isolated workspace. Every branch has its own copy of the project history and develops on its own code. They are easily and often merged with each other.</td>
    </tr>
    <tr>
        <td>Master</td>
        <td>The primary branch of all repositories. A master is the main default local branch when the project is first created as a git project. All committed and accepted changes should be on the master branch. You can work directly from the master branch, or create other branches.</td>
    </tr>
    <tr>
        <td>HEAD</td>
        <td>HEAD is a reference variable used to denote the most current commit of the repository in which you are working. When you add a new commit, HEAD will then become that new commit.</td>
    </tr>
    <tr>
        <td>checkout</td>
        <td>The <b><i>git checkout</i></b> command is used to switch branches in a repository. <b><i>git checkout branch_name</i></b> would take you to that particular branch whereas <b><i>git checkout master</i></b> would drop you back into master. Be careful with your staged files and commits when switching between branches.</td>
    </tr>
    <tr>
        <td>Clone</td>
        <td>A clone is a copy of a repository or the action of copying a repository.</td>
    </tr>
    <tr>
        <td>Fetch</td>
        <td>By performing a Git fetch, you are downloading and copying that branch’s files to your workstation. Multiple branches can be fetched at once, and you can rename the branches when running the command to suit your needs.</td>
    </tr>
    <tr>
        <td>Fork</td>
        <td>Creates a copy of a repository.</td>
    </tr>
    <tr>
        <td>Merge</td>
        <td>Taking the changes from one branch and adding them into another (traditionally master) branch.</td>
    </tr>
    <tr>
        <td>Origin</td>
        <td>The conventional name for the primary version of a repository. Git also uses origin as a system alias for pushing and fetching data to and from the primary branch. For example, <b><i>git push origin master</i></b>, when run on a remote, will push the changes to the master branch of the primary repository database.</td>
    </tr>
    <tr>
        <td>Pull/Pull Request</td>
        <td>If someone has changed code on a separate branch of a project and wants it to be reviewed to add to the master branch, that someone can put in a pull request. Pull requests ask the repo maintainers to review the commits made, and then, if acceptable, merge the changes upstream. A pull happens when adding the changes to the master branch.</td>
    </tr>
    <tr>
        <td>Push</td>
        <td>Updates a remote branch with the commits made to the current branch. You are literally “pushing” your changes onto the remote.</td>
    </tr>
    <tr>
        <td>Rebase</td>
        <td>When rebasing a git commit, you can split the commit, move it, squash it if unwanted, or effectively combine two branches that have diverged from one another.</td>
    </tr>
    <tr>
        <td>Remote</td>
        <td>A copy of the original branch. When you clone a branch, that new branch is a remote, or clone. Remotes can talk to the origin branch, as well as other remotes for the repository, to make communication between working branches easier.</td>
    </tr>
    <tr>
        <td>Tag</td>
        <td>Tags are used to define which portions of a project’s Git history is most important. Often this is used to note point releases of a project. Tags can be added to the commit you are working with or added after-the-fact when needed.</td>
    </tr>
    <tr>
        <td>Upstream</td>
        <td>While there is not necessarily a default “upstream” or “downstream” for Git projects, upstream can be considered where you push your Git changes — this is often the master branch of the project within the origin</td>
    </tr>

</table>

<br>

<p align="center">
    <img src="https://media.giphy.com/media/P7PmvHY6kzAqY/giphy.gif" width="300">
    <br>
    Understanding and remembering these Git Terms is not that easy <br>But with time and practice you will definitely master it.
</p>