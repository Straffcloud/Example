# Example
Git Workflow Management


1. Create the repository and clone it to my local computer

2. Create a new branch called starter code if I need to add starter code
    - git checkout -b <branch name>

3. Make my changes under the branch, and push them to the cloud
    - git status (to see changes)
    -git add . (if you want to add all the changes)
    -git commit -m"<description>"
    -git push
    -git push --set upstream <branch name>

4. Create a pull request and merge the code
    - If an issue is open, make sure that you assign it to the branch

5. Switch to computer main branch and sync to the cloud
    - git checkout main
    -git pull

6. Repeat steps 2 - 6