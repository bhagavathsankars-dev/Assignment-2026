# Git Exercise Writeups - bass

# 1. intro
Started the exercise using git start and checked my solution using git verify.

# 2. commit-one-file
I learned how to stage and commit only one specific file instead of all files.

# 3. commit-one-file-staged
I learned how to unstage a file that was already staged and commit only what I wanted.

# 4. ignore-them
I created a .gitignore file and wrote rules in it to tell Git which files to ignore like .exe, .o, .jar files and the libraries folder.

# 5. chase-branch
I used git merge to make one branch catch up to another branch that was ahead of it.

# 6. merge-conflict
Two branches changed the same file differently so Git didn't know which to keep. I opened the file, fixed it manually by keeping the correct version, then committed the fix.

# 7. save-your-work
My work was unfinished when a bug came up. I used git stash to save 
my work aside, fixed the bug, committed it, then used git stash pop 
to get my work back and finished it.

# 8. change-branch-history
I used git rebase to move my branch so that it starts from the bugfix commit instead of the original starting point.

# 9. remove-ignored
A file was being tracked by Git even though it should be ignored. I used git rm --cached to tell Git to stop tracking it without deleting the actual file.

# 10. rename-file
I renamed a file using git mv so that Git properly tracks the rename instead of seeing it as a deleted and new file.

# 11. fix-typo
I made a typo in a file that was already committed. I fixed the typo and used git commit --amend to update the last commit instead of making a new one.

# 12. forge-date
I changed the date of a commit to 1987 using the --date option with git commit --amend.

# 13. fix-old-typo
The typo was in an old commit, not the latest one, so --amend was not enough. I used git rebase -i to go back to that specific commit, fixed the typo, amended it, resolved a conflict that came up, and completed the rebase
