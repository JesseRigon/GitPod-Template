# GitPod-Template

This template simply uses this repo as the control center for a project being worked on using the GitPod CDE.

For Example if you set up the template the folder structure under /workspace in GitPod should be:

  - .dotfiles
    - .git
    
  - GitPod-Template
    - .git
    - .gitpod.yml
    - main.code-workspace
    
  - ProjectDir
    - .git
    
    
As you can see each directory has its own .git. This lets you work on multiple projects within the same IDE screen while being able to not have a mono repo structure.

This also allows you to keep you ProjectDir clean of gitpod files.
