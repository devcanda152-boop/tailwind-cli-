1. git remote -v
Use:
Shows the remote repositories connected to your local project.

Output:
If nothing is shown → no remote was set yet.

2. git init
Use:
Initializes a new Git repository in the current folder.

What it does:
Creates a hidden .git folder
Starts version control for the project

You run this once per project.

3. git remote add origin <URL>
git remote add origin https://github.com/....git

Use:
Connects your local repo to a GitHub repository.
origin → default name for remote
URL → GitHub repo link

Required before pushing code to GitHub

4. git add .
Use:
Stages all files for commit.

Meaning:
“I want to include these files in the next commit.”
. = all files in the folder

5. Warning (LF → CRLF)
LF will be replaced by CRLF

Meaning:
Git is warning about line ending changes

Common on Windows
 Not an error
 Safe to ignore.

6. git commit -m "msg"
Use:
Saves a snapshot of staged files.

git commit -m "msg"

-m → commit message

"msg" → description of changes

Example:
git commit -m "Add Tailwind CSS build file"

7. git push origin main

Use:
Uploads your commits to GitHub.

Breakdown:
origin → remote repo
main → branch name

First push creates the branch on GitHub.

8. git brach (Typing mistake)

What happened:
Git didn’t recognize the command.

Correct command:
git branch

9. git branch

Use:
Lists all local branches.

Output:
development
* main
* main → currently active branch
development → another branch

10. git checkout development

Use:
Switches to another branch.
git checkout development

Meaning:
“Move from main branch to development branch.”

Your files now reflect the development branch state.