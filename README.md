# GitHub HandBook
**[GitHub](http://github.com)** is a development platform for version control and collaboration. It allows you to host and manage your projects and work together on same projects from anywhere.

Well let’s start with a few basics.
## Terminology

| Keyword | Description |
| ---| --- |
| **Repository** | **"Repo"** for shortv is a folder for storing your codes, files, text files, image files, etc. It can be local folder on your computer, or a storage space on GitHub. |
| **Fork** | A copy of someone else's project or repository. Forking makes it possible for you to freely experiment the project **WITHOUT** affecting the original project. |
| **Upstream** | The original repo or Project that you have forked |

Repositories
Branches
Commits
Pull Requests

## [What is Git?](https://www.atlassian.com/git/tutorials/what-is-git)

It is basically a **Version Control System** which helps us to have a multiple versions of our project every point of time to avoid losing or overwriting it.
If you are working together on the same projects then **Git** will help you to:
- Save your codes online.
- See what new changes are made by all developers
- Discuss issues with other developers
- Recovering deleted datas
- Revert accidentally changed data.
- Share and exchange code with other developers easily.
- Backup your code easily to a remote server.
- **And Many more**

# Getting Started
## Sign Up on GitHub

Refer to this [Link](https://github.com/join?source=header-home)

<table>
  <tr>
    <td><strong>Select New Repository</strong><br/><br/>
    <ul><li>Upper right corner</li>
  <li>Select New repository</li>
    </ul>
    </td>
    <td> <p align="left">
       <img src="p4.png" width="350">
    </p>
    </td>
  </tr>
  
  <tr>
    <td><strong>Create a Repository</strong><br/></br>
<ul>
  <li>Name it</li>
  <li>Provide a Short description</li>
  <li>Select Initializewith a README.</li>
      </ul>
    </td>
    <td> <p align="left">
       <img src="p3.PNG" width="550">
    </p>
    </td>create a new branch
  </tr>
<tr>
  <td colspan="2"><strong><h2>BRANCH</h2></strong>
    <p align="justify">
      We use Branching to work on different versions of a repository at one time. The default <strong>BRANCH</strong> is named as <strong>MASTER</strong>. We create new branches which can be said as a copy of Master branch and we do our experiments there before committing them to master. Any changes done in your new branches will not be reflected in your master branch. But if someone made a change in your master branch then you could pull in those updates to your branch. When the code is ready, you can merge all of your branch into master.
    </p></br>
    <td>
 </tr>
   <tr>
    <td><br/><strong>Create a New Brach</strong><br/></br>
<ul>
  <li>Go to your new repository</li>
  <li>Drop down (branch: master)</li>
  <li>Type a branch name</li>
  <li>Select the blue branch box</li>
      </ul>
    </td>
    <td> <p align="left">
       <img src="p6.png" width="550">
    </p>
    </td>
  </tr>
 
 
 <tr>
  <td colspan="2"><strong><h2>COMMIT</h2></strong>
    <p align="justify">
     Commits are basically saving your changes. For each commit you can add a commit message and a small description explaining the changes made so that other contributors will understand why you made the change. In short Commits prepares a history of your changes. Thus helping you to see your previous codes.
    </p></br>
    <td>
 </tr>
   <tr>
    <td><br/><strong>Create Commit</strong><br/></br>
<ul>
  <li>Click the README.md file</li>
  <li>Click the  pencil to edit</li>
  <li>Write something</li>
  <li>Add a commit message </li>
  <li>Add a description</li>
   <li>Click Commit changes button.</li>
      </ul>
    </td>
    <td> <p align="left">
       <img src="p7.png" width="550">
    </p>
    </td>
  </tr>
  
  <tr>
   <td colspan="2"><p><br/>You have a <strong>MASTER</strong> Branch and <strong>DEMOEDITS</strong> Branch. These changes will be made to just the README file on your <strong>DEMOEDITS</strong> branch and not on your <strong>MASTER</strong> Branch.</p><br/>
  </td>
  <tr>
    
   <tr>
  <td colspan="2"><strong><h2>PULL REQUEST</h2></strong>
    <p align="justify">
Now it's time for pull request. You can open a pull request in your own repository and then merge it to your master branch. But mainly we use pull request to propose your changes to someone interested. If someone review your code they will pull in your contribution to their branches. You can easily figure out the differences of the content from both branches.
    </p></br>
    <td>
 </tr>
   <tr>
    <td><br/>Click the  Pull Request tab<br/><br/>Click New Pull Request</br>
    </td>
    <td> <p align="left">
       <img src="p8.PNG" width="550">
    </p>
    </td>
  </tr>
    <tr>
  <td><br/>In the <strong>Example Comparisons box</strong>,<br/><br/>select your branch <br/>Compare with the Master Branch.</strong><br/></br>
    </td>
    <td> <p align="left">
       <img src="p9.PNG" width="550">
    </p>
    </td>
  </tr>
  
  <tr>
  <td><br/>click Create Pull Request button.</br>
    </td>
    <td> <p align="left">
       <img src="p11.PNG" width="550">
    </p>
    </td>
     <tr>
    <td><br/>Give a title and a brief <br/><br/>description of your changes.</br>
    </td>
    <td> <p align="left">
       <img src="p12.PNG" width="550">
    </p>
    </td>
  </tr> 
  </tr>
    <tr>
    <td><br/>Click Merge pull request<br/><br/>Click Confirm Merge</br>
    </td>
    <td> <p align="left">
       <img src="p10.PNG" width="550">
    </p>
    </td>
  </tr>
    <tr>
    <td><br/>Delete your Branch<br/></br>
    </td>
    <td> <p align="left">
       <img src="p13.PNG" width="550">
    </p>
    </td>
  </tr>
</table>

## Git and GitHub on Windows
[Download](https://git-scm.com/downloads) and install [Git](https://git-scm.com/downloads)

<table>
  <tr>
    <td>Search for Git Bash
    </td>
    <td> <p align="left">
       <img src="p1.png" width="550">
    </p>
    </td>
  </tr>
  
  <tr>
    <td>Type git --version
    </td>
    <td> <p align="left">
       <img src="p2.PNG" width="550">
    </p>
    </td>
  </tr>
  
  <tr>
  <td colspan="2"><br/>Go to Desktop and create a folder <strong>"git"</strong>. Open the folder and right Click, select <strong>Git Bash Here</strong><br/><br/>
    </td>
  </tr>
   <tr>
    <td colspan="2"><br/>Create a Respository Online. Follow instruction above<br/><br/>
    </td>
  </tr>
  
  <tr>
    <td>Click Clone or Download <br/><br/>
     Copy the URL 
    </td>
    <td> <p align="left">
       <img src="pp2.PNG" width="550">
    </p>
    </td>
  </tr>
  
  <tr>
    <td> git config --global user.name "Your Name" <br/><br/>
git config --global user.email "youremail@domain.com" <br/><br/>
git clone (Paste the URL)
 <br/><br/>
    </td>
     <td> <p align="left">
       <img src="pp3.PNG" width="550">
    </p>
    </td>
  </tr>
  
   <tr>
    <td colspan="2"><br/>Go to the "git" folder and there you go. All files in your local folder<br/>
 <br/>
  </tr>
  
   <tr>
    <td colspan="2"> <br/>Go inside the new folder.
      In my case its <strong>"GitHub-HandBook" and create a file "hello.txt"</strong>
 <br/><br/>
  </tr>
  
  <tr>
    <td> type cd "folder name" <br/><br/>
git add hello.txt <br/><br/>
git status <br/><br/>
git commit -m "(committed message)" "filename"<br/><br/>
git push -u origin master <br/><br/>
      Provide your credentials <br/>
      <br/>
  There you go, Refresh your <br/>GitHub Online Account to see the new file

 <br/><br/>
    </td>
     <td> <p align="left">
       <img src="pp4.PNG" width="550">
    </p>
    </td>
  </tr>
</table>
<br/>


