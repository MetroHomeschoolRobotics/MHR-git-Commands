# MHR-git-Commands
Repo to hold all of our most used git commands for our source control management. 

Pull down a created repository 

``git clone <https://url.com>``


Track all files in folder. The astrick means include all. 

``git add <filename>``


Commit any changes in folder. 

``git commit -am <notes on commit>``


Push all changes up to repository. 

``git push``


This will print out a list of commits with their message and ID. 
Locate the version you would like to view and use this command...

``git log`` 


Switch the active Branch with:

``git checkout <branch_name>``


Remove all local changes: 

``git reset --hard origin/<branch_name>``


# Overwrite target branch with contents of feature branch

``git checkout <feature_branch_name>``

``git merge -s ours <target_branch_name>``

``git checkout <target_branch_name>``

``git merge <feature_branch_name>``

_Copied from: https://gist.github.com/ummahusla/8ccfdae6fbbe50171d77_
