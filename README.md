# github_usage
notes about github usage


### Tutorial
#### [Git-it](http://jlord.us/git-it/)
- Get git
  - Install
  
    Windows: It's recommended to download GitHub for Windows, which includes Git and has an easier install: [windows.github.com](http://windows.github.com/). Use the Git Shell for your terminal.
    
    Mac: You can also download GitHub for Mac, which includes Git, mac.github.com (from Preferences, select the command line tools install), or download Git by itself at: [git-scm.com/downloads](http://git-scm.com/downloads) and follow the installation instructions.
  
  - Configure
  
    Open **terminal** (or Bash)
    - Verify installation:  `$ git --version`
    - Set name: `$ git config --global user.name "<Your Name>"`
    - Set email: `$ git config --global user.email "<youremail@example.com>"`
    
- Repository
  
  A _**repository**_ is essentially a project. You can imagine it as a project's folder with all the related files inside of it. In fact, that's what it will look like on your computer anyways.
  
  - Create a Repository
  
    - To make a new folder: `$ mkdir hello-world`
    - To go into that folder: `$ cd hello-world`
    - To create a new Git instance for a project: `$ git init`
    - Verify if it's a Git repo: `$ git status`
  
- Commit it
  - Create a New File, e.g. readme.txt under hellow_world folder
  - Status, Add and Commit Changes
    - Check repo status: `$ git status`
    - Add file to do commit: `$ git add readme.txt` (tell git which file you gonna commit)
    - Commit file: `$ git commit -m "<your commit message>"`
  - Make More Changes
    -  view the difference between the file now and how it was at your last commit : `$ git diff`

- Use GitHub
  - Create a GitHub Account : [github.com](http://github.com/)
  - Add username to Git
  
    Add your GitHub username to your Git configuration : `$ git config --global user.username <USerNamE>`
  
- Remote Control
  
  Connect your local and remote repositories and push changes. (push / pull)
  - Create a Remote Repository   
    - Create a new repo on Github, make it's name exactly same as your local repository's name. 
    - Make it public.
    - Don't initialize with a README because we already have a file, locally, named 'readme.txt'.
    - Leave .gitignore and license on 'none'.
  
  - Connect your Local to your Remote : `$ git remote add origin <URLFROMGITHUB>`
  - Push Work to your Remote : `$ git push origin master`
  

