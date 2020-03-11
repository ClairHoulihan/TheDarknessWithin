# The Darkness Within
Project Design Doc found at https://drive.google.com/drive/folders/1GgdkMyqrJAF6LdZKTrCgTcpLxRCvIciT?usp=sharing

# Installations
Make sure you have the follwing 

Unity v2019.3.3f1
git for your terminal or a git GUI such as GitKraken or GitHub for Desktop
If you ever get an error message about LFS (Large File System) make sure it is installed in your computer. 

# Set-up Unity Editor 
Before you start pulling or pushing anything for the first time, do the following:

    Edit > Project Settings > Editor

In the inspector on the right side of the window:
    
    Set the Version Control to: Visible Meta Files
    Set the Asset Serialization: Force Text

Click Save/Apply. 

Note:
    
    -The .gitignore file does most of the excluding of unity workstation dependent files and executibles
    -Git will only save the files that are within the /Assets folder in the editor. So if you are adding new scenes, materials, prefabs, etc., please add them to their respective folder under the /Assets hierarchy 
    
# Using GitKraken
1. Sign into your Github Account to use GitKraken (or make a GitKraken account)
2. Clone the repository
3. Select the directory path for the local copy
3. Select the project /HorrorGame

# Using Version Control with Unity
    -At every iteration of development we shall each be given a task(s) to complete. 
    -To start work on your given task(s) please create a new branch in the repository. Switch to that branch. Any work done within the branch will not affect the Master branch.
    -Once you are done with your tasks or just wish to save progress, push changes to your branch. 
    -Ideally we want to merge your branch to Master once you are completely done. 
    -If everyone is done, we merge all branches and fix the issues then proceed to the next iteration.
    -Do NOT delete any asset used by others unless you have cleared it up with whoever is also using what you want to delete. 
