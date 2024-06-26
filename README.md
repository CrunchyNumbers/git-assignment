Git Assignment - CrunchyNumbers
a. What is an issue
An issue is a way to track ideas, enhancements, tasks, bugs, or other types of information in a GitHub repository. It serves as a communication tool among the repository's contributors, allowing them to discuss changes or report problems. Issues can be assigned, labeled, and commented on, and they may also have milestones or deadlines associated with them.


b. What is a pull request?
A pull request is a request to merge changes from one branch into another branch (typically the main branch). When you create a pull request, it allows others to review your code, discuss changes, and suggest improvements before merging the changes into the main codebase. It is a collaborative tool used to ensure code quality and facilitate communication.


c. How do I open up a pull request?
To open a pull request on GitHub:
1. Push your changes to a new branch on GitHub:
     git push origin your-branch-name
2. Go to the GitHub repository in your browser.
3. Click on the Pull requests tab.
4. Click the New pull request button.
5. Choose the base branch (usually main) and the compare branch (the branch you pushed changes to).
6. Add a title and description for the pull request.
7. You can assign reviewers, labels, or milestones if desired.
8. Click the Create pull request button to open the pull request.


d. Give me a step-by-step guide on how to add someone to your repository.
To add someone as a collaborator to your repository:
1. Go to the repository on GitHub.
2. Click on the Settings tab.
3. In the left sidebar, click on Manage access.
4. Click the Invite a collaborator button.
5. Enter the GitHub username of the person you want to add.
6. Choose the appropriate permission level for the collaborator (e.g., read, write, or admin).
7. Click Add to send an invitation to the user.
The user will need to accept the invitation before they are added as a collaborator.


e. What is the difference between Git and GitHub?
Git is a distributed version control system that allows you to track changes in your codebase, collaborate with others, and manage multiple versions of your project.
GitHub is an online platform that provides hosting for Git repositories and additional collaboration tools such as pull requests, issue tracking, and project management features. It serves as a central hub for repositories and makes it easy to share and collaborate on projects with others.


f. What does git diff do?
'git diff' shows the differences between the working directory and the index, or between the working directory and a specified branch or commit. It allows you to see changes made to files, such as additions, deletions, and modifications. It can also compare different branches, commits, or files.


g. What is the main branch?
The main branch (formerly known as the master branch in most projects) is the primary branch in a Git repository. It is where the stable version of the code resides and is typically the default branch for new repositories. Development is often done on feature or topic branches and then merged back into the main branch once the code is reviewed and tested.


h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?
In general, you should avoid pushing changes directly to the main branch, especially in a collaborative project. Instead, use feature branches to develop changes, and then create pull requests to merge them into the main branch. This workflow allows for code review and testing before changes are incorporated into the main branch, helping maintain code quality and stability.
