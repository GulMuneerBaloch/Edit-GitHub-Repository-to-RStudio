# Edit-GitHub-Repository-to-RStudio
Create a new repository in GitHub and edit it in RStudio
On GitHub, create a new repository (github.com > Your Profile > Repositories > New). Name your new test repository and give it a short description. Click Create repository. Copy the URL for your new repository.
![image](https://user-images.githubusercontent.com/59471339/113387240-7fac4e00-93be-11eb-80d9-697a4e2e1f46.png)
In RStudio, go to File > New Project. Select Version Control. Select Git as your version control software. Paste in the repository URL from before, select the location where you would like the project stored. When done, click on “Create Project”. Doing so will initialize a new project, linked to the GitHub repository, and open a new session of RStudio.
![image](https://user-images.githubusercontent.com/59471339/113387542-18db6480-93bf-11eb-8127-0c990fade118.png)
**Creating a version controlled project on RStudio**
![image](https://user-images.githubusercontent.com/59471339/113387568-21339f80-93bf-11eb-96c6-f8e4861ef801.png)

Cloning your Git repository to RStudio

Create a new R script (File > New File > R Script) and copy and paste the following code:

print("This file was created within RStudio")

print("And now it lives on GitHub")

Save the file. Note that when you do so, the default location for the file is within the new Project directory you created earlier.
![image](https://user-images.githubusercontent.com/59471339/113387648-504a1100-93bf-11eb-8145-9ad16787ed30.png)

Saving your first script for this project

Once that is done, looking back at RStudio, in the Git tab of the environment quadrant, you should see your file you just created! Click the checkbox under “Staged” to stage your file.

![image](https://user-images.githubusercontent.com/59471339/113387671-5cce6980-93bf-11eb-9fd2-a80fa4da81ca.png)

Saving your first script for this project

Once that is done, looking back at RStudio, in the Git tab of the environment quadrant, you should see your file you just created! Click the checkbox under “Staged” to stage your file.


![image](https://user-images.githubusercontent.com/59471339/113387790-943d1600-93bf-11eb-8082-3004a44f5381.png)

All files that have been modified since your last pull appear in the Git tab

Click “Commit”. A new window should open, that lists all of the changed files from earlier, and below that shows the differences in the staged files from previous versions. In the upper quadrant, in the “Commit message” box, write yourself a commit message. Click Commit. Close the window.




![image](https://user-images.githubusercontent.com/59471339/113388039-0ada1380-93c0-11eb-916b-3cd0344e9431.png)



Commiting your R Script to the repository!

So far, you have created a file, saved it, staged it, and committed it. If you remember your version control lecture, the next step is to push your changes to your online repository. Push your changes to the GitHub repository.




![image](https://user-images.githubusercontent.com/59471339/113388322-9784d180-93c0-11eb-9f91-c0c1acea1980.png)


How to push your commit to the GitHub repository

Go to your GitHub repository and see that the commit has been recorded.

You’ve just successfully pushed your first commit from within RStudio to GitHub!

Summary
we created a repository on GitHub, linked it with a new project within RStudio, created a new file, and then staged, committed, and pushed the file to your GitHub repository!


