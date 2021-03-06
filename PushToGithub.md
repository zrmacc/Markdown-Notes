Pushing to Github
================
Zachary McCaw
2018-07-20

#### Steps for pushing local repository to `github`

1.  **Initialize** `git` in local directory: `git init`
    -   To clear an existing initialization of `git` use: `rm -rf .git`

2.  **Add** files in the local repository to the staging area: `git add .`
    -   Use `git status` to view the staging area

3.  **Commit** files in the staging area: `git commit -m "First commit"`
    -   View commit history using `git log`

4.  Create the remote repository on `github`
5.  **`add`** a `remote` repository named `origin` at a specified `SSH` address, for example: `git remote add origin git@github.com:zrmacc/Notes.git`
    -   Check registered remotes `git remote -v`
    -   **Remove** a remote `git remote rm <name>`

6.  **Push** current state of local repository to `master` branch of `origin` repository: `git push origin master`
    -   In the case of conflicts, to force the push use `git push -f origin master`
