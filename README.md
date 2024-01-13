# Teachable
Task 2 Git/GitHub

# Explain version control.
1.Version control is a systematic approach to tracking and managing changes to files over time, particularly in collaborative projects. It allows multiple contributors to work on a project concurrently, maintaining a history of modifications. This method helps in managing different versions of the code or documents and provides tools for tasks such as branching, merging, conflict resolution, and history tracking. Popular version control systems include Git and SVN. In essence, version control systems play a crucial role in ensuring the integrity, collaboration, and effective management of software development projects.

# Explain difference between git and github.
Git is the version control system itself, managing the history and changes of project locally, and enables collaboration among developers.

GitHub, on the other hand, is a platform built around, It provides hosting for Git repositories, offering a web-based interface and collaborative features to enhance the development workflow, making it easier for teams to work together on projects.

# List 3 other github alternatives.
- Gitlab:
- Bitbucket:
- Sourceforge:
 
# Explain the difference between git fetch and git pull.
Git fetch:

Retrieves changes from a remote repository to a local repository.
Fetches new branches, tags, and modifications in existing branches but doesn't automatically merge them into your current working directory.
Useful for inspecting changes on the remote before deciding to merge them locally.
  
Git pull:

Fetches changes from a remote repository and automatically merges them into your current working branch.
Essentially combines the actions of git fetch and git merge.
Offers a convenient way to quickly update your local working copy with changes from the remote.

# Explain in simple terms git rebase and the command for it.
Git rebase is a command used to combine changes from one branch into another, making your project history look more linear and clean.

Here's the command for it:
git rebase target_branch

This command takes the changes from your current branch and integrates them onto the specified target_branch. It can be useful for maintaining a cleaner and more straightforward history in your Git project.
	
# Explain in simple terms git cherry-pick and the command for it.
Git cherry-pick allows you to pick and apply specific changes (commits) from one branch and add them to another branch.

Here's the command for it:

git cherry-pick <commit_hash>

This command takes the changes made in a specific commit (<commit_hash>) and applies them to your current working branch. It's handy when you only want to bring in certain changes from one branch to another.