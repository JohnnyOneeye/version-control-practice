# version-control-practice

Git and GitHub “push” means sending your committed changes from your local repository
on your computer to a remote repository a repository on GitHub
When you push your commits are uploaded so that other people can see them and collaborate on the project.
In the GitHub web interface commits are often saved directly to the online repository so there is no separate push step required.

It is better to fix mistakes with a new commit because it keeps the complete history of changes.
This allows you and other developers to see what was changed when it was changed and why
Keeping the history also makes it easier to track down problems and understand the development process
while deleting history can remove important information and make collaboration more difficult.

safest way to undo changes is to create a new commit that corrects the mistake
because it preserves the project's history and avoids rewriting existing commits.

Revert means to undo the changes from a previous commit.
Git creates a new commit that reverses those changes while keeping the project history intact.

In systems like Git:
Delete removes a file from the project.
Revert creates a new change that undoes a previous commit while preserving the project's history.

They are especially useful because they let you:

Track progress clearly you can see how your project evolved step by step.
Fix mistakes safely if something breaks you can go back to a previous working version.
Experiment without risk you can try new ideas knowing you can undo them if needed.
Collaborate effectively other people can understand your changes through commit messages.
Maintain accountability each change is documented so it’s clear who changed what and why.

In short commits make your work organized, reversible and understandable which is essential for both individual development and team projects.

Use clear commit messages

Clear commit messages are important because they explain what changed and why:

Improves understanding: Other developers and your future self can quickly understand what each change does.
Speeds up debugging: When a bug appears commit messages help narrow down where the issue might have been introduced.
Supports collaboration team members can review work more efficiently when changes are clearly described.
Creates a useful project record: Good messages form a readable history of the project’s development over time.
