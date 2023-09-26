# git_assignment


---

1. **Initialize a Git Repository:**
   - `git init`: Initializes a new Git repository in the current directory.

2. **Clone a Repository:**
   - `git clone [repository_url]`: Creates a copy of a remote Git repository on your local machine.

3. **Status and Information:**
   - `git status`: Shows the status of your working directory and staged changes.
   - `git log`: Displays the commit history.
   - `git branch`: Lists all branches in the repository.
   - `git remote -v`: Lists remote repositories associated with your local repository.

4. **Adding and Committing Changes:**
   - `git add [file(s)]`: Adds changes to the staging area in preparation for a commit.
   - `git commit -m "Commit message"`: Commits staged changes with a descriptive message.

5. **Branching and Merging:**
   - `git branch [branch_name]`: Creates a new branch.
   - `git checkout [branch_name]`: Switches to an existing branch.
   - `git merge [branch_name]`: Merges changes from one branch into the current branch.
   - `git branch -d [branch_name]`: Deletes a branch.

6. **Remote Repositories:**
   - `git remote add [name] [repository_url]`: Adds a remote repository with a custom name.
   - `git push [remote_name] [branch_name]`: Pushes local commits to a remote repository.
   - `git pull [remote_name] [branch_name]`: Fetches and merges changes from a remote repository.

7. **Undoing Changes:**
   - `git reset [file]`: Unstages changes for a specific file.
   - `git reset --hard [commit_id]`: Resets the working directory and staging area to a specific commit.

8. **Working with Tags:**
   - `git tag [tag_name]`: Creates a lightweight tag at the current commit.
   - `git tag -a [tag_name] -m "Tag message"`: Creates an annotated tag with a message.
   - `git push --tags`: Pushes tags to a remote repository.

9. **Git Help:**
   - `git --help`: Displays the built-in Git documentation.
   - `git [command] --help`: Shows help for a specific Git command (e.g., `git commit --help`).

10. **Configuration:**
    - `git config --global user.name "Your Name"`: Sets your Git username globally.
    - `git config --global user.email "your.email@example.com"`: Sets your Git email globally.

These are some of the most common Git commands to get you started. Remember to replace `[repository_url]`, `[branch_name]`, `[file]`, `[commit_id]`, and `[tag_name]` with the appropriate values for your specific use case.


---


**Assignment Title:** Git Version Control Basics

**Objective:** Gain practical experience with Git version control by completing the following tasks.

**Instructions:**

**Task 1: Setup and Configuration**

1. Install Git on your computer if it's not already installed. You can download Git from [https://git-scm.com/](https://git-scm.com/).

2. Open a terminal or command prompt and configure your Git username and email globally using the following commands (replace "Your Name" and "your.email@example.com" with your actual name and email):

   ```
   git config --global user.name "Your Name"
   git config --global user.email your.email@example.com
   ```

3. Use the `git config --list` command to verify your Git configuration. Take a screenshot of the terminal showing the configuration and submit it.

**Task 2: Creating a Repository**

1. Create a new directory on your computer called "GitAssignment."

2. Navigate to the "GitAssignment" directory using the terminal.

3. Initialize a Git repository in this directory using the `git init` command.

4. Create a new text file named "README.md" in this directory.

5. Add some text content (e.g., a brief description of your assignment) to the "README.md" file.

6. Use `git status` to check the status of your repository. Take a screenshot of the terminal showing the status and submit it.

**Task 3: Committing Changes**

1. Add the "README.md" file to the staging area using the `git add` command.

2. Commit the changes to the repository with a meaningful commit message using the `git commit` command.

3. Use `git log` to view the commit history. Take a screenshot of the terminal displaying the commit history and submit it.

**Task 4: Creating and Switching Branches**

1. Create a new branch named "feature-branch" using the `git branch` command.

2. Switch to the "feature-branch" using the `git checkout` or `git switch` command.

3. Add a new file named "feature.txt" to this branch.

4. Commit the "feature.txt" file to the "feature-branch."

5. Use `git log --oneline --graph --all` to visualize the branch history. Take a screenshot of the terminal showing the branch history and submit it.

**Task 5: Merging Branches**

1. Switch back to the main branch (usually called "main" or "master") using `git checkout` or `git switch`.

2. Merge the changes from the "feature-branch" into the main branch using the `git merge` command.

3. Resolve any merge conflicts if they occur.

4. Commit the merge.

5. Use `git log --oneline --graph --all` again to visualize the updated branch history. Take a screenshot of the terminal showing the updated branch history and submit it.

**Submission 1:**

1. Create a zip file containing all the screenshots and any additional files used for the assignment.

2. Write a brief summary of your experience with Git, mentioning any challenges you faced and how you overcame them.

3. Submit the zip file and summary


---

**Assignment Title:** Git Collaboration and Workflow

**Objective:** Gain hands-on experience with Git collaboration workflows by completing the following tasks.

**Instructions:**

**Task 1: Forking and Cloning**

1. Visit a public GitHub repository of your choice (e.g., an open-source project).

2. Fork the repository to create your own copy on GitHub.

3. Clone your forked repository to your local machine using the `git clone` command.

4. Verify that the clone was successful by navigating to the cloned repository directory in your terminal.

**Task 2: Branching and Collaboration**

1. Create a new branch in your local repository. Name it "feature-implementation."

2. Add a new file named "feature.txt" to this branch and write some content in it.

3. Commit the "feature.txt" file to the branch with a meaningful commit message.

4. Push this branch to your forked repository on GitHub using the `git push` command.

5. Create a Pull Request (PR) from your "feature-implementation" branch to the original repository's main branch (or an appropriate branch) on GitHub.

6. Add a description to your PR explaining the changes.

**Task 3: Review and Merge**

1. Ask a friend or classmate to review your Pull Request. If you don't have someone to review it, you can use a secondary GitHub account to simulate a review.

2. Have the reviewer comment on your PR, suggesting improvements or acknowledging its quality.

3. Make any necessary updates to your branch based on the reviewer's feedback.

4. Commit these updates and push them to your branch on GitHub.

5. Request another review from the same person or a different individual.

6. After receiving approval (or simulating it), merge the Pull Request on GitHub.

**Task 4: Fetch and Sync**

1. In your local repository, switch back to the main branch.

2. Use the `git fetch` command to check for updates from the original repository.

3. Create a new branch named "sync-branch" from the main branch.

4. Merge the latest changes from the original repository's main branch into your "sync-branch."

5. Commit the merge, and push the "sync-branch" to your forked repository on GitHub.

**Submission 2:**

1. Provide the URL to your forked repository on GitHub.

2. Include the link to the Pull Request you created in Task 2.

3. Describe the feedback you received from the reviewer(s) in Task 3 and how you addressed it.

4. Summarize the steps you took to sync your repository with the original repository in Task 4.


