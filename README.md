# A02
Part 1: Directions on Using WebStorm with Git and GitHub

Step 1: Download and Install WebStorm

  Go to the official JetBrains website: https://www.jetbrains.com/webstorm/

  Click on "Download" and choose the appropriate version for your operating system.
  
  Follow the installation instructions provided on the website.

Step 2: Install Git

  Visit https://git-scm.com/ to download Git.
    
  Select your operating system and download the latest version.
    
  Install Git by following the installation instructions.
    
  Verify the installation by opening a terminal or command prompt and running:
    
  git --version

Step 3: Configure Git

  Set your name and email:
  
  git config --global user.name "Your Name"
  git config --global user.email "your.email@example.com"

Step 4: Create a New Repository on GitHub

  Go to https://github.com/
  
  Log in or create an account.
  
  Click the "+" icon in the top-right corner and select "New repository".
  
  Provide a name for your repository.
  
  Choose public or private.
  
  Click "Create repository".

Step 5: Clone the Repository in WebStorm

  Open WebStorm.
  
  Click on Get from VCS (Version Control System).
  
  Select GitHub and sign in with your GitHub account.
  
  Enter the repository URL and click Clone.
  
  Step 6: Make Changes and Commit
  
  Open your project in WebStorm.
  
  Make necessary changes in your code.
  
  Go to VCS > Commit.
  
  Write a meaningful commit message.
  
  Click Commit.

Step 7: Push Changes to GitHub

  Go to VCS > Git > Push.
  
  Select the branch and click Push.

Step 8: Pull and Fetch Changes

  To update your local repository with changes from GitHub:
  
  Go to VCS > Git > Pull to get the latest changes.
  
  Go to VCS > Git > Fetch to check for updates without applying them immediately.

Step 9: Merging and Resolving Merge Conflicts

  If working on multiple branches, use VCS > Git > Merge Changes.
  
  If a Merge Conflict occurs, WebStorm will prompt you to resolve it manually.
  
  Edit conflicting files and select which changes to keep.
  
  Commit the resolved changes.

Step 10: Using Branches

  Create a new branch via VCS > Git > Branches > New Branch.
  
  Switch branches and merge changes when necessary.

Part 2: Glossary

  Branch: A separate version of the repository, allowing for parallel development.
  
  Clone: A local copy of a remote repository.
  
  Commit: Saving changes to the repository with a descriptive message.
  
  Fetch: Retrieving changes from a remote repository without merging them.
  
  GIT: A distributed version control system used for tracking changes in code.
  
  GitHub: A web-based platform for hosting Git repositories.
  
  Merge: Combining changes from different branches into one.
  
  Merge Conflict: A situation where Git cannot automatically resolve differences between branches.
  
  Push: Uploading local changes to a remote repository.
  
  Pull: Downloading and integrating changes from a remote repository.
  
  Remote: The online version of a repository stored on a platform like GitHub.
  
  Repository: A storage location for code and version history.

References

  https://www.jetbrains.com/webstorm/

  https://git-scm.com/

  https://docs.github.com/en


