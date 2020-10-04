# Submitting assignments using github
In this course, in addition to the lecture notes being hosted on github, all assignments will be submitted via a github repository.

For the weekly assignments, a shared private github repository will be used: https://github.com/ds4geo/ds4geo_ws2020
You will have been invited to this repository by email.
As this repository is shared, you will be able to see assignment submissions by other students. This is intentional for two reasons:
1. We will discuss submitted assignments in class.
2. You are encouraged to share and look at each other's code as a way of learning, just as you are encouraged to use google and stackoverflow for help, code snippets and inspiration. However, you should indicate by comments any code or ideas you have coppied from classmates. Github saves the complete "commit" history, so it is easy to see and prove who is copying without acknowledgement.
Note: you also technically can edit other student's assignments, but any edits are recorded and tagged to a user. Later in the course we will cover collaborate code development.

For the main project, you should set up your own github repository which will itself be the submission. Details will be provided later.


# How to submit assignments
## Creating files (not notebooks!) directly in GitHub
You can create text files directly in GitHub as follows:
![Create file](https://github.com/ds4geo/ds4geo/blob/master/res/Create_file.png)

Files with a .md extension are "markdown" files. Markdown is a simple text formatting system which is also used for text cells in Jupyter Notebooks. For more information see here:
https://guides.github.com/features/mastering-markdown/

You can also edit existing .md or text files by clicking the pencil (edit file) button:
![Edit file](https://docs.github.com/assets/images/help/repository/edit-file-edit-button.png)

When done creating or editing, commit the changes (see below).

## Uploading files into GitHub
Uploading works like creating new files. Click "Add file" then "Upload files", follow the instructions and commit the new files (see below).

## Commiting (saving) files in GitHub
Saving files or edits in GitHub is called "commiting". When creating, uploading or editing a file, at the bottom is the commit dialog:
![Commit file](https://github.com/ds4geo/ds4geo/blob/master/res/commit_file.png)

In the top text box you should write a short message describing the edit.
In the second box you can optionally include a longer description.
Leave the box "Commit directly to master branch" selected (we will cover what this means later in the course)
Click the green "Commit" button to save.


## Creating Jupyter Notebooks in Colab and saving them to a GitHub Repository
Most assignments will require you to submit a Jupyter Notebook by saving it to a GitHub Repository. You can do this as follows:

1. Go to Google Drive (and log in), click "New", "More", "Google Colaboratory":
![create new colab doc](https://i2.wp.com/contentsimplicity.com/wp-content/uploads/2019/03/369ef-d0a1d-1sjfggypnyhpafndbna7edg.png?w=1080)

2. You will now have an empty Jupyter Notebook. You can then rename it and add content. It will automatically be saved to your Google Drive.
![new colab doc](https://github.com/ds4geo/ds4geo/blob/master/res/new_colab.png)

3. When you are ready to save it to GitHub, click "File", "Save a copy in GitHub. You will then be asked to log in to your GitHub account if you are not already.

4. You will then see this dialog:

![new colab doc](https://github.com/ds4geo/ds4geo/blob/master/res/copy_to_github.png)

* You can then select the repository (e.g. ds4geo_ws2020 for submitting an assignment).
* Ignore the "Branch" selection.
( Enter the file path and file name. For example, for submitting the week 2 assignment, you would put (with your own name):
"/Assignments/Session 2/barrett.ipynb"
* Leave "Include link to Colaboratory" ticked (blue)

*note: you can always submit a new version later and overwrite the existing GitHub copy*

## Opening a Jupyter Notebook from GitHub in Colab
There are two options to open a Notebook on GitHub in Colab:
1. If there is an "Open in Colab" button displayed in GitHub, simply click it.
2. Open Google Colab then use "File", "Open Notebook", "GitHub".
