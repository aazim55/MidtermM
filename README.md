Exam on Introduction to engineering and computer science
Make a fork of this repository on your GitHab. Read the tasks carefully and complete them according to the instructions.
✔️ All tasks must be done on the git and uploaded to the GitHub.

✔️ Send me a link to your GitHub repository with the completed tasks in a telegram message: @AntigravityApple.

✔️ In the next message after the link send me information about who you are: name, surname and group.

⚠️ Don't do Pull request.

⚠️ Your push operation may not work. If so you can use FORCE PUSH. How to do force push you can find in internet, or use https url.

⚠️ The end of the exam is at 12:30.

❌ I will not accept links that are sent later than end of the exam

❌ I will not accept a links if you send me your GitHub instead of a repository with answers.

❌ I will not accept links unless you post information about who you are.

Tasks:
Task 1️⃣: Create new branch "Student_name" and add 2 commits.

Task 2️⃣: Recreate the graph as in the picture. Leave a link to the repository in the text file "task 2".

Task 3️⃣: Rebase branch two to branch one and merge three to one. Show the process in screenshots

Task 4️⃣: Answer the question in commit question.
TASK 3
1-What is the difference between switch and checkout?
2-What does git merge do?
3-What happens to the commit history after rebase and why?
4-How to understand which branch is remote and which is local in the terminal?
ANSWERS
1-`git switch` is used specifically for switching branches, making it simpler and more focused. `git checkout` is a multi-purpose command that can switch branches, check out commits, and stage files, but it can be more confusing due to its many functions.
2-`git merge` combines changes from one branch into the current branch, integrating the histories of both branches.
3-After a rebase, the commit history is rewritten, appearing as if the rebased commits were made on top of the target branch’s latest commits. This creates a linear, cleaner history by avoiding merge commits, making it look like all changes happened sequentially.
4-In the terminal, run `git branch` to see local branches and `git branch -r` to view remote branches. Remote branches usually have the prefix `origin/`.