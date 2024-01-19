Each company has its own best practices for git, and they can be numerous. Each team has specific standards, but we think these basic “best practices” are globally accepted. Not having set criteria in place prior to beginning a project is a recipe for disaster. If you are new to Git, it may take some time to get used to these practices. Eventually, these specifications will make perfect sense. As time goes on, you will adopt other procedures that better suit your workflow.

___1. Branching is Imperative!___
Individual team participants can be assigned to different Git branches. This allows them to work concurrently but in a separate and isolated environment. Branch names should always be relevant to the task, so other team members know precisely what is being worked on.
Branches are the perfect tool to avoid mixing different lines of development. Branching also alleviates conflicts when merging workflows. Branches should be used extensively in our development process. It should be used for new features, bug fixes, experiments, or ideas.
If there are old branches that are no longer needed, we can remove them without any risk of losing changes. These branches are unnecessary clutter and make it more difficult for people to work with the existing components in the repository.

___2. Stay Updated___
Always have the most current version of your project in the master repository. Before working on new features, that are created or assigned to a team member, always commit. Conflicts could arise when merging branches if updates do not occur regularly. We prefer to use a Testing >> Staging >> Production type development cycle.

___3. Keep Repositories Easy to Understand___
“Commit” small changes frequently. Frequent commits allow team members to check and verify modifications promptly. 
When adding a commit, keep the commit message descriptive and understandable. Start the commit comment with a short summary and separate it from the body with a blank line. This prevents guesswork when trying to understand previous changes.
Don’t commit generated files unless using a .gitignore file. We can list ignored files that are not required for the repository. Especially if they contain sensitive data (passwords, configuration files, etc.)

___4. Stash your Work___
Suppose we find ourselves in a situation where we work on one branch and need to make a change in a different branch quickly. Because the alteration is imperative to the initial branch’s relevance, we can use “git stash.”
This command lets us save our unfinished changes in a stack where we can retrieve it anytime! Stash also allows us to save ideas for that one “feature” that popped in our mind late last night. Since we do not want to commit half-completed work, we can use stash. 

___5. Squash and Merge___
To create a cleaner commit history, we can squash and merge commits into a single one when pull requests are finally merged. Because each pull request can have multiple commits, having fewer commits in history makes it easier to track down issues if something goes wrong later.
