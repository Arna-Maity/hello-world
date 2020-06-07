# hello-world
1st repository to get started with GitHub. This repo contains a set of handy git commands to enable beginners to get started with Open Source Development & Version Control.

0. #### First Time Setup ( After installing Git. )

    `git config --global user.name <your-name>`

     This name will be displayed against the commits you create.

    `git config --global user.email <your-registered-email>`

1. #### Intialize a new local git repository.

   `git init`

2. #### Adding a remote repository to push all your changes to GitHub.
    `git remote add origin <http-link-of-the-git-repo>`

3. #### Add files from working area to staging area.

    `git add <filename> | -A`

    Using the ' -A ' option instead of specifying a file name will transfer all the unstaged changes to the staging area.

4. #### Commit changes from the staging area to the final commited stage.

    #### NOTE: No further changes/modifications allowed after the changes are commited. 

    `git commit -m "<a-brief-message-about-the-commit>"`

5. #### View the status of staged and unstaged changes in your git repo.

    `git status`

6. #### View a history of the commits you've made to your repo.

    `git log`


## Contributions

Contributions are welcome.

This guide is under active development and i will be adding newer commands as time progresses. Presently, i have only included those commands which are the bare minimum for getting started with version control. Meanwhile, if you find some other git command which you would want to include in this guide, feel free to open a pull request will all the necessary changes.

