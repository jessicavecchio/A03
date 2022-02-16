#A03
<!DOCTYPE html>
<html>
  
  <h1>What is git?</h1>
  <p>"A specific open-source version control system created by Linus Torvalds in 2005."
    It is a "distributed version control system" which means the entire code and its history is available on every developer's computer. This allows for easy branching and merging.</p>

  <h1>What is webstorm?</h1>
  <p>"Webstorm is an integrated development enviornment for coding..." 
    Webstorm offers support for: JavaScript, TypeScript, React, Vue, Angular, Node.js, HTML, style sheets, and more.
    Webstorm includes a smart editor that is able to complete code, and detect erros. 
    It includes tools to help debug, work with version control, linters, build tools, terminal, and HTTP client. 
    Webstorm helps improve teamwork due to its "remote collaborative development and pair programming and the ability to share your project configuration with others."</p>
   <p>Sourced from: https://www.jetbrains.com/help/webstorm/meet-webstorm.html </p>

  <h1>What is github?</h1>
  <p>"GitHub is a website and cloud-based service that helps developers store and manage their code, as well as track and control changes to their code."
    Github is an open source version control.
    Version control is something that helps developers keep track of and manage a software project's code. 
    Anyone can make an account and post public repositories for free.</p>
  <p>Sourced from: https://kinsta.com/knowledgebase/what-is-github/ </p>


  <h1>Directions on Using WebStorm:</h1>
  <ol>
    <li>Download Webstorm at: https://www.jetbrains.com/student/</li>
    <li>Install Git as a local program at: https://git-scm.com/</li>
    <li>Create a Github account at: https://github.com/join</li>
    <li>Connect Github with Webstorm:</li>
      <ul>
        <li>In Webstorm, go to system preferences</li>
        <li>Select version control Git and enter the path to the git.exe</li>
    </ul>
    <li>Add Github password to Webstorm:</li>
      <ul>
        <li>In Webstorm, go to system preferences</li>
        <li>Select apppearance and behavior</li>
        <li>Select system settings</li>
        <li>Select passwords</li>
    </ul>
    <li>Create a repository:</li>
    <ul>
      <li>Click the + sign in the upper right corner</li>
      <li>Choose "create new repository</li>
      <li>Make the repository public</li>
      <li>Add a readMe file</li>
      <li>Click create</li>
    </ul>
    <li>Create a repository from Webstorm:</li>
    <ul>
      <li>Select VCS and import into version control</li>
    </ul>
    <li>Import a repository from Github:</li>
    <ul>
      <li>From Webstorm, select VCS</li>
      <li>Select checkout from version control</li>
      <li>Select Git</li>
      <ul>
        <li>OR</li>
      </ul>
      <li>From main, select checkout from version control</li>
      <li>Select Git</li>
    </ul>
      <ul>
        <li>Enter Github repository name</li>
        <li>Enter local path name</li>
      </ul>
    <li>Creating a Webstorm file:</li>
    <ul>
      <li>Select File</li>
      <li>Select HTML</li>
      <li>Select HTML 5</li>
      <ul>
       <li>OR</li>
      </ul>
      <li>Select File</li>
      <li>Select Stylesheet</li>
    </ul>
    <li>Add files to Git:</li>
    <ul>
      <li>The 'Add to Git' dialog opens</li>
      <li>Click add - this creates a local file system</li>
    </ul>
    <li>Commit your changes!</li>
    <li>Push changes to remote repository:</li>
    <ul>
      <li>Click CTRL, Shift, and K</li>
      <ul>
       <li>OR</li>
      </ul>
      <li>Select VCS, then Git, then Push</li>
    </ul>
    <li>Your file is now on Github!!</li>
    <li>Setting up Github pages:</li>
    <ul>
      <li>Select settings</li>
      <li>Check your repository name</li>
    </ul>
    <li>Choose your Github page location</li>
    <ul>
      <li>Select 'Master Branch'</li>
      <li>Take notes of the published URL</li>
    </ul>
    <li>Check your Github pages</li>
    <ul>
      <li>Copy the Github.io URL into a browser</li>
    </ul>
    <p></p>
    <p></p>
    <p>Sourced from: Introduction to Github and Webstorm by Arthur H. Hendela, Ph.D. Senior University Lecturer, NJIT</p>


  <h1>Glossary:</h1> 
    
<ul>
  <li>Branch:</li>
  <p> When a developer duplicates part of the source code. This allows the developer to make changes safely without changing the original file</p>
  
  <li>Clone:</li>
  <p>A copy of a repository that is housed on your computer instead of on a website server</p>
  <p>When you edit the copy, you can use your editor and Git to keep track of changes</p>
  <p>Since the clone is connected to your remote version, you can push your changes to the remote to keep them synced</p>
  
  <li>Commit:</li>
  <p>A revision or change to a file</p>
  <p>When you make a change, Git creates a unique ID that allows you to keep a record of the changes including who made them and when</p>
  <p>The commits usually include a description of what changes were made</p>
  
  <li>Fetch:</li>
  <p>Adding changes from remote repository to your local branch without committing them</p>
  <p>This allows you to review your changes before committing to your local branch</p>
  
  <li>GIT:</li>
  <p>An open source program that is used to track changes in text files</p>
  <p>Created by the author of Linux</p>
  <p>Core tech that Github is built on</p>
  
  <li>Github:</li>
  <p>"GitHub is a website and cloud-based service that helps developers store and manage their code, as well as track and control changes to their code."</p>
  <p>Github is an open source version control</p>
  <p>Version control is something that helps developers keep track of and manage a software project's code</p>
  <p>Anyone can make an account and post public repositories for free</p>
  
  <li>Merge:</li>
  <p>Moving the code back to the main source code in order to finalize the code</p>
  <p>Takes changes from one branch and applies to another</p>
  <p>Happens as a pull request</p>
  
  <li>Merge Conflict:</li>
  <p>A difference that happens between merged branches</p>
  <p>This happens when people make changes to the same line of the same file or when someone edits a file that was deleted by someone else</p>
  <p>A merge conflict has to be resolved before you can merge the branches</p>
  
  <li>Push:</li>
  <p>Sending your comkmitted changes to a remote repository on GitHub.com</p>
  
  <li>Pull:</li>
  <p>Asking someone in charge of a branch of the repository to include your code in it</p>
  <p>Fetching changes and merging them</p>
  
  <li>Remote:</li>
  <p>A version of a repository or branch that is on a server</p>
  <p>Remote versions can be connected to local versions so changes can be synced</p>
  
  <li>Repository:</li>
  <p>The source code</p>
  <p>Most basic element of GitHub</p>
  <p>A project folder</p>
  <p>Contains all files apart of a project</p>
  <p>Stores each file's revision history</p>
  <p>Can be public or private and edited by multiple people</p>
  
  </ul>
  <p>Sourced from: https://docs.github.com/en/enterprise-server@3.0/get-started/quickstart/github-glossary </p>




  <h1>Sources:</h1>
 
  <ul>

    GitHub glossary. GitHub Docs. (n.d.). Retrieved February 16, 2022, from https://docs.github.com/en/enterprise-server@3.0/get-started/quickstart/github-glossary
    Introduction to Github and Webstorm by Arthur H. Hendela, Ph.D. Senior University Lecturer, NJIT
    Meet Webstorm: Webstorm. WebStorm Help. (n.d.). Retrieved February 16, 2022, from https://www.jetbrains.com/help/webstorm/meet-webstorm.html
    What is github? A beginner's introduction to github. Kinsta®. (2021, May 28). Retrieved February 16, 2022, from https://kinsta.com/knowledgebase/what-is-github/
    
  </ul>
 
  
  
  </html>
  



