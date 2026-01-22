# Linux and Git Cheatsheet

## Linux Commands:

- **`mkdir`:** creates a new directory
  - **Syntax:** *`mkdir` \<directory name\>*

- **`cd`:** changes the current directory
  - **Syntax:** *`cd` \<directory name\>*

- **`pwd`:** displays the present working directory
  - **Syntax:** *`pwd`*

- **`cat`:** concatenation tool—typically used for quickly outputting the contents of a file
  - **Syntax:** *`cat` \<filename\>*

- **`touch`:** creates an empty file in the current directory
  - **Syntax:** *`touch` \<filename\>*

- **`rm`:** deletes a file or directory. Use the `-r` flag to delete recursively (i.e. all files and folders in a directory)
  - **Syntax:** *`rm` \(-f\) \<filename\>*

- **`mv`:** moves a file or directory. You can also use this to rename files
  - **Syntax:** *`mv` \<filename\> \<destination\>*

- **`man`:** displays the manual page for a given command.
  - **Syntax:** *`man` \<command\>*
  
## Git Commands:
*Note: All git commands listed below are understood to be prefaced by `git`. For example `git init`*

- **`init`:** initializes a new git repository in the current directory
  - **Syntax:** *`git init`*

- **`status`:** displays the current state of the working directory and staging area
  - **Syntax:** *`git status`*

- **`add`:** adds files to the staging area to be included in the next commit
  - **Syntax:** *`git add` \<filename\>*

- **`commit`:** save a snapshot of the staged changes to the working directory. i.e. create a "save point". Use the `-m` flag to add a commit message at the command line
  - **Syntax:** *`git commit [-m] "Commit message"`

- **`push`:** upload (push) committed changes from the current branch to a remote repository. Use the `--all` flag to push all branches
  - **Syntax:** *`git push` [--all] \<remote name\>*

- **`pull`:** download (pull) committed changes from a remote repository
  - **Syntax:** *`git pull` \<remote name\>*

