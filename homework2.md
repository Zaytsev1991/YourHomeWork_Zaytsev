__BRANCHES__

___this line is needed for different types of merging, it will be explained further
this line should have been written in the master___

* _creating branches and switching to them_

    If you want to create a branch, then enter (_git branch < name of your branch >_)

    To view the branches, enter (_git branch_)  

    To switch to another branch, enter (_git checkout < name of your branch >_)

* _merging branches in the state fast-forward_

    Merging _Fast-Forward_ is when the elements of a branch go into the main body without disputes, following each other

    With such a merge, a commit about this is created automatically

* _merging branches in the state ort strategy_

    If, during the merge, the master changes not only in the part of the body going further, but also in the part of the master before, while not creating a conflict, the merge will occur

    In this case, after the merge, you no need to create a commit

    At the same time, the difference in the master and the branch is combined

* _conflicts and their resolution_

    1. selecting a specific branch

        If there is a conflict, when the work is carried out in one area, there is an option to choose what will be the final one, an option in the branch or the master

    2. combining branches

        Don't forget to write a commit after resolving the conflict
        
        Also, in case of a conflict, you can combine and leave all the options together

## GITHUB

If you want to create a remote repository, then at the beginning you will need to create your account on github

Then create a new repository in your account, and then describe it in the VScode. After that, you will need to link the new repository to yours using the command (push)

To interact with someone else's repository, you need to go directly into it and create a fork, thereby creating a kind of side branch to someone else's file in the repository

In that cloned fork, you need to create your own branch so that after you edit the source document, you can send this branch to merge with the original

Thank you!