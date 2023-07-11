https://stackoverflow.com/questions/33488085/how-to-get-a-new-branch-in-my-fork-from-the-original-repository

git remote add OriginalRepo repository-URL
git fetch OriginalRepo
git checkout newBranch
git push origin newBranchv