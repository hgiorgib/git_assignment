# Git Assignment - hgiorgi

### *a. What is an issue?*
An issue on GitHub is like a to-do list item or a bug report. It helps keep track of things that need to be done, whether it's fixing a bug, adding a feature, or just asking a question. Issues are great for organizing work and discussing ideas with the team.

### *b. What is a pull request?*
A pull request (PR) is how we propose changes to a repository. When we’re ready for someone to review our work, we create a pull request. It’s essentially saying, “Hey, I’ve made these changes. Can you take a look and, if all looks good, merge them into the main code?”

### *c. Describe the steps to open a pull request?*
-1. *Start with a New Branch:* Don’t work on the main branch directly. Create a new branch for our changes.
-2. *Make Our Changes:* Do our coding on this new branch.
-3. *Commit our Changes:* Save our work with a commit, and make sure to write a good commit message explaining what we’ve done.
-4. *Push the Branch to GitHub:* Send your branch with the changes to GitHub.
-5. *Open the Pull Request:* Go to the repository on GitHub, click the "Pull Requests" tab, and hit "New Pull Request". Compare your branch with the main branch, describe what you’ve changed, and create the PR.
-6. *Wait for Review:* Once submitted, others can review your PR, suggest changes, or approve it.

### *d. Describe the steps to add a collaborator to a repository (share write permissions):*
-1. *Go to Your Repo:* Open the repository we want to share.
-2. *Settings:* Click on the "Settings" tab at the top.
-3. *Manage Access:* In the sidebar, find "Collaborators and Teams".
-4. *Add Collaborator:* Click "Add people" and enter the GitHub username or email of the person we want to invite.
-5. *Set Permissions:* Choose their access level, usually "Write" if we want them to contribute code.
-6.*Send Invitation:* They’ll get an invite, and once they accept, they’ll have access to the repo.

### *e. What is the difference between git and GitHub?*
-Git is the tool that tracks changes in our code. It’s a version control system that we use locally to manage your code’s history.

-GitHub is a platform that hosts Git repositories online. It’s where we can share our code, collaborate with others, and use extra features like issues, pull requests, and CI/CD tools.

### *f. What does git diff do?*
git diff shows us the differences between our current changes and the last commit. It’s like a snapshot of what we’ve changed but haven’t committed yet. We can also use it to compare branches, specific files, or commits to see exactly what’s different.

### *g. What is the main branch?*
The main branch is the primary branch of our repository. This is where the final, stable version of the code lives. It’s the version that usually gets deployed or shared with users, so it’s important to keep it clean and bug-free.

### *h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?*
Not usually. It’s better to create a new branch for our changes and open a pull request to merge them back into main. This way, our code can be reviewed, tested, and approved before it affects the main branch. It helps prevent bugs and keeps things organized.
