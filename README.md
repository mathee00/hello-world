# hello-world
Hi! Hello! Bonjour!👋

## All the instructions to clone a GitHub repo

  First copy the pathe of the folder which you want to clone and open the path in the cmd.
  Type `cd` and past the path.
  
  <img src = "https://github.com/mathee00/hello-world/blob/main/Images%20of%20GitHub%20cloning/Config%20path.PNG" width = "700">
  
  Then copy the HTTP link from the repo (code)
  
  <img src = "https://github.com/mathee00/hello-world/blob/main/Images%20of%20GitHub%20cloning/Copying%20the%20Repo%20link.PNG" width = "400">
  
  Type `git clone` and past the link.
  
  <img src = "https://github.com/mathee00/hello-world/blob/main/Images%20of%20GitHub%20cloning/Cloning%20the%20folder.PNG" width = "900">
 
  
  After cloning we can see the contents by typing `dir`
  
  <img src = "https://github.com/mathee00/hello-world/blob/main/Images%20of%20GitHub%20cloning/Viewing%20the%20content.PNG" width = "700">
  
  In the end the github repo will be in your folder where you cloned.




## Adding files to a GitHub repo
  When you drag and drop a folder/file into a cloned folder (cloned GitHub repo), you need to save those changes in the GitHub as well. These are the four steps on adding a folder/file.
  
  ### First step - To find untracked files, type the below command
  
   `git status` you will get a similar output as below
   
   <img src = "https://github.com/mathee00/hello-world/blob/main/adding/git%20status(Finding%20untracked%20files).PNG" width = "700">
   
   Remember to be in the correct folder, otherwise you'll get this error
   
   <img src = "https://github.com/mathee00/hello-world/blob/main/adding/be%20in%20the%20correct%20folder.PNG" width = "700">
   
  ### Second step - Add the folder/file to the index (stagging area)
  
    git add <<file name>>
    
  <img src = "https://github.com/mathee00/hello-world/blob/main/adding/git%20add.PNG" width = "700">
  
  You can view the changes to be commited by typing below commad
  
   `git status` you will get a similar output as below
   
   <img src = "https://github.com/mathee00/hello-world/blob/main/adding/Changes%20to%20be%20commited.PNG" width = "700">
   
   ### Third step - Commit the changes with a commit message 
   
    git commit -m "<< commit message >>"
    
   You will get a similar output as below
   
   <img src = "https://github.com/mathee00/hello-world/blob/main/adding/git%20commit.PNG" width = "700">
    
   ### Final step - Push the changes to the GitHub repo (Publishing local commits)
   
    git push
    
   You will get a similar output as below
   
   <img src = "https://github.com/mathee00/hello-world/blob/main/adding/git%20push.PNG" width = "700">
    
  
  ## Debugging errors on push
  
  If you get a error similar to this, you might have cloned the repo with the HTTP link. To over come this error always clone with the SSH link(passphrase - 1511).
  
  ### Error
  
  <img src = "https://github.com/mathee00/hello-world/blob/main/adding/error%20on%20push/git%20push%20error.PNG" width = "700">
  
  ### Solution
  
    git config --global http.postBuffer 524288000
    
  <img src = "https://github.com/mathee00/hello-world/blob/main/adding/error%20on%20push/Solution.PNG" width = "900">
  
  Some times the value might be doubled
  
    git config --global http.postBuffer 1048576000
 
  ### Successful push
  
  <img src = "https://github.com/mathee00/hello-world/blob/main/adding/error%20on%20push/A%20successful%20push.PNG" width = "700">
  
  
  ## Other info

  All the images for my wiki pages (including veracity dev repos wikis) are here

