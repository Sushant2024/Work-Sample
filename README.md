# Work-Sample
Here I will develop web pages for a site, just for practice purpose. 
https://github.com/Sushant2024/Work-Sample/projects/1#column-6520106

# Steps on complete Working of git right from installation

After installing:
- Open cmd.exe **or** git cmd interface
- Make new folder as **Workstation for your work** and other commits/ **Open Project directory that you are working on.**
- Go to **current_working_directory** using the command **'cd', 'cd..', 'dir'** that is the folder you are working on.
- **git init** : This will create a ".git" hidden folder
- **git status** : Shows the files (_It will appear in red if files are available_)
- **git add file_name** : Adds the file named "**file_name**" to git (_On rechecking of "git status", the entered file will turn green_)
- **git commit -m "Comment_the_changes_that_you_made"** : Use to add comment to remember the changes (_Do not forget to use **write comment in between double quotation, don't miss " " double_quotation_.**)

# Some common commands in "git"

- _git add *.extension_ :- To add all files with the entered extension example: _git add *.txt_ will add all text files.
- **git add .** :- To add all files of that folder that have not been included or added yet.
- **_Doesn't work always_** :- **touch file_name.extension** : This command is used to create a new file (Eg: **touch index.html** _This will make a new **html_file** named **index_**)

- **git log** : Shows your activities or changes made on git.
- **git --help** : Shows all the option that you have for github.
- **dir> file_name.extension** makes a file with given _file_name_ based on extension type.

# Creating "Remote Repository on Git hub"

- Click **+** icon and select "new repository"
- Give a _name_ to the repository and select _public_.
- Copy the repository by clicking on "pad icon" infront of location link below Repository_name.
- In cmd at _Working directory_ : **git remote add origin Location_of_remote_repository** _paste the copied url link to repository (i.e, location of repository)_
- To push the changes to _master or main branch_ : **git push -u origin master** (This will add files & folders to the "code_section" on git-hub).
