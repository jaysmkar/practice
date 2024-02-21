# Practice

Some steps to push the code on github:- 
1. git init -- to add the existing repository as the git repository
            -- git adds one folder .git which will be the hidden folder which will contain all the git files which are software related.
            -- also add the files and turn onn the untracked mode "U"

2. git clone <HTTP URL> -- to clone the remote url the the local machine 
                        -- it will clone all the data from the remote to local machine incase some changes are done than it will autopull those 

3. git status -- to check the git status 

4. git add . -- to add the modified files to git
             -- converts the untracked mode to added mode i.e. "A"

5. git commit -m "commit message" -- save the changes to the git/say git be ready to push the changes to remote 

6. git push origin main -- push the changes to remote and generates the hexadecimal code for the same version of code 

For using git you can also use git commands through github desktop but using git from terminal is standard followed in industry.


## Branching in GIT

7. git branch <new_branch> -- to create new branch
                           --  this is used to give it to some other team/member where some other development work is going onn.
                           -- this branch can be merged to the main branch once everything is okay with respect to code over there.

8. git checkout <branch_name> -- used to switch from one branch to another branch 

NOTE: The newely created branch won't be available until the changes in that perticular branch is pushed on remote platforms.
    Newley created branches won't be affecting the main branch



## Advantages of branching and pull requests:
-- You can collaberate with the team members to maintain the performance on the peak always.
-- Once the specific developement is done you can merge the pieces of code via pull requests.
-- It will let other people to know what is going in your project.

Garbage Branches: Many times it happens that branch is created but noone is working on it for may be any reason these types of branches are called as dead branches, happening this is very normal in practice as it won't affect the product or service anymore;
    



=============================================================================================

