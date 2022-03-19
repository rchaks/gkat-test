# gkat-test

This is some useful information

## Notes

### Create github repository
- https://github.com/

### Clone github repo

`git clone git@github.com:rchaks/gkat-test.git`

> NOTE: if need be, follow these steps to setup authentication: https://docs.github.com/en/authentication/connecting-to-github-with-ssh/about-ssh

### Making your first change

1. Make sure you're on the main branch: 
   `git checkout main`
2. Get the latest version of main
   `git pull`
3. Create a new branch
   `git checkout -b <name_of_branch>`
4. Make your change; add it to your branch LOCALLY
   ```
   git add -A
   git commit -m "My helpful commit message"
   ```
5. Push the changes to github.com
   ```
   git push -u origin <name_of_branch>
   ```