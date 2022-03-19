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

### Create Pull Request (through GUI)

base: main, compare with: <name_of_branch>

### Wait for approval or request changes
#### Assuming changes are required
1. Make changes
2. Commit them `git add -A; commit --amend`
3. `git push --force`

### Once approved, merge through GUI, switch back to mainline & delete the old feature branch
1. git checkout main
2. git pull
3. git branch -d <name of branch>

###

Rinse & repeat

