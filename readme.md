# This is a demo on using git and github

## Steps
### Setup
1. Create project
2. Convert the project into a local repository or initialize it as local repo
```bash
git init
```
 - Setup user name and email
 ```bash
git config --global user.name "johnverz22"
git config --global user.email "johnny.verzola@lorma.edu"
```
3. Create a remote repo on GitHub 
4. Connect local and remote so they'll in sync
```bash
git remote add origin <repo-link>
```
5. Push or upload local changes to remote repo
```bash
git add .                      # stage all changes
git commit -m "Description"    # commit all staged changes
git push -u origin main        # or next time just run git push 
```


### Development