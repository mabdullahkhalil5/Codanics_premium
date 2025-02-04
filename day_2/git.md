# Steps to use git

1. install git from this [link](https://git-scm.com/downloads/win)
2. make a folder in your hard drive locally
3. go to that folder via command prompt or terminal
   ```git
   cd <path to folder>
   ```
4. initialize_git_repository
   ```
   git init
   ```
5. add changes to the stage changes
   ```
   git add <path_to_file>
   ```
   or, use this command to stage all changes at once
   ```
   git add .
   ```
6. commit the changes if you are done with changes
   ```
   git commit -m "your message"
   ```
7. to sync changes use this:
   ```
   git push
   ```