# GIT

root@escbash-lab:~/journal# git restore --staged draft.txt
root@escbash-lab:~/journal# git status --short
A  day1.txt
A  day2.txt
A  day3.txt
?? draft.txt
?? scratch.txt
root@escbash-lab:~/journal#
*****************************************************************
Commands this lesson introduced
git diff --cached shows what the next commit will contain.
git diff HEAD shows all changes since the last commit.
git add -p stages changes hunk by hunk.

*********************
git diff compares working files against the staging area. It answers: what have I edited but not staged yet?
git diff --cached compares the staging area against HEAD. It answers: what will my next commit contain?
git diff HEAD compares working files against HEAD. It answers: what changed in total since the last commit?

<img width="615" height="153" alt="image" src="https://github.com/user-attachments/assets/cf4e7467-962d-4ed5-bc24-214f893b73e4" />
