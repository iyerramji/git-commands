# git-commands
A reference for myself of various git commands



# Commands that I have used in the past

    http://2buntu.com/articles/1459/keeping-your-forked-repo-synced-with-the-upstream-source/
    git fetch upstream
    git rebase upstream/master
    git push origin master
    git checkout --track origin/TiMOS-DC_3_2_current
    git reflog
    git rebase --interactive upstream/master
    git -reset upstream/master
    git clean -fdx


# Theory for reference
    git --version
    git config --global user.email "xyz_learner@example.com"
    git config --global user.name "xyz Learner"
    git add .
    git commit -m "my message"
    git reset --soft HEAD~1
    git reset --hard HEAD~1
    git branch my_new_branch
    git checkout new_branch
    git checkout -b new_branch
    git branch -m authentication_feature ( renaming)
    git branch -m new_branch authentication_feature
    git branch -d new_branch
    git stash
    (switch branch and ) git stash apply
    git merge <branch_to_be_merged>
    git remote add <name> <url_to_remote_repository>
    git push <remote_repository> <branch_name>
    git clone <link_to_repository>
    git clone --branch <branch_name> <link_to_repository>
    git clone <repository_url> --depth 1
    git fetch origin
    git merge origin/master
    git pull origin branch_name
    git rebase <parent_branch>
    more than one guy working on a branch then dont rebase
