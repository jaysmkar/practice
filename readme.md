## The DVC guide is here 

1) git init -- to initialize the git repository
            -- it would start trackin the code files in the repository

2) dvc init -- to initialize the dvc repository  
            -- will create the .dvc directory inside the file which contains the metadata about the dvc 

3) git commit -m 'commit_message' -- commiting the addition of the dvc folder and its metadata to the git 
                                  -- till here nothing is related to the dvc rather initializing the dvc

4) dvc add <data_path> -- adding the data to the dvc 
                       -- it would create the data.txt.dvc file which is the reference to the actual data folder 
                       -- this folder is created inside the same data folder where actual data is stored 
                            
                            data.txt.dvc -- it contains the hash key can say the version of the data 
                            based on the containt of data you can create the hash key 
                            



DVC is only used to track the data files not the code
    -- rather than adding the entire code to the git it is always a good idea to add the reference file to the data that will be data.dvc file to git 

.dvc/config -- will contain all the information about remote repositories where the data needs to be added. 
.gitignore --

