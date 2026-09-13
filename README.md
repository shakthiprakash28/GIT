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
