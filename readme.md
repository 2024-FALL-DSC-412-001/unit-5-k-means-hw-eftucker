# Getting Started

Make sure your terminal is in this directory. You can confirm that is true by typing `pwd` in terminal.

Create a virtual environment with

`python -m venv ./.venv`

Then activate it in terminal:

Windows: `.\.venv\Scripts\activate`

Mac: `source ./.venv/bin/activate`

Linux: `source ./.venv/bin/activate`


You should see `.venv` appear in the terminal on the left side of teh command line.

# Explaining What is going on

Hopefully you have this open in VS Code. If not you should have gotten a link to clone this repo onto your computer. You can then open the folder (the repo) that was cloned in VS Code. Use the "Mark Down All in On" Extension to open this readme.md file to see it easier. The button should be in the top right area of the screen. 

# What will be graded?

Please see the rubric in the assignment for what will be graded.


# Saving and Grading your Code

How do you upload and grade your code? 
<br><br>

One way you got this starter template was through using Github. Github is a place where code is stored online and shared in *repos*. It helps other developer's not reinvent the wheel, and use other people's Python tools to accelerate their works. 

We will being using Github to upload your code to your personal repo.

Below I will explain how to upload your code. There are multiple of the same explanations below.

There are 3 basic steps to uploading your code, and they are are placed in terminal. 

1.) Adding to stage

2.) Committing from stage

3.) Pushing commit to online repo 

# Using Terminal to submit

Make a change to your homework file.

*Make sure all your files are saved*

In terminal type:

`git add <files>`

***or*** you can bring in all files with 

`git add -A`

This means: github add -A (all) files to *stage*

Stage is where files can then be committed.
You can check what is staged by using `git status` in terminal. 

`git commit -m "<some message>" `

This will commit any code you have staged. If you forget the -m and message, press `:q!` and try again. If that does not work press "esc" multiple times then type in `:q!` again.

Then finally 
`git push` 
will push your commit to the github repo. 

<br><br>
Another way to think about this:

A *commit* is a package we would like to upload online.

*stage* is like a temporary places to hold what we want to commit. 

We create the package using the `add` command to add code to *stage*

Once we are done adding code to *stage*, we can then seal the package with the `commit` command. We give the commit a message like `commit -m "some message"`

We then need to send the package online, so we call `push`, which pushes your code into your repo 

<br><br>
All 4 commands used in order: 

`git status`, can be called anytime to see what is in stage

`git add <file path>` or `git add -A`, can stage specific files or use `-A` to stage all files (-A is recommended for now)

`git commit -m "some message"`, sealing stage in a commit with an attached message

`git push` push the commit to online branch. 

You can call as many commits before a push as you would like. You can also push as many new commits as you want. 

Here is a general workflow:

Modify file_we_want_to_grade.py

You want to grade file_we_want_to_grade.py

`git add <files>`

`git commit -m "new: some comment about implementation"`

`git push`

file_we_want_to_grade.py




