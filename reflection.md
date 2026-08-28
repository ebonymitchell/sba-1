Steps taken to create and manage branches:
I created branches using the following command:
git checkout -b [branch name]

I managed branches using the following commands:
git switch [branch name] or git checkout [branch name] to change branches
git branch to view all available branches
git merge [branch name] to merge named branch into current branch

How I handled the merge conflict:
When the merge conflict arose, I used the editor to accept or correct the conflicting changes. I then staged the resolved file and committed the changes.

How the pull request process helped me ensure code quality and collaboration:
When attempting to create the pull request in GitHub, I received the message "There isn't anything to compare. main and review/main are identical." This indicated that there were no differences between the two branches because review/main was created after the changes had already been committed and merged into main.

Additional considerations: After creating the branch review/main, I added the reflection.md and peer review documents to the main branch. These changes created a difference between main and review/main, allowing me to create a pull request and review the changes between the two branches.