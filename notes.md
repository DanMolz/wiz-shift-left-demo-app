1. Create Pull Request
git checkout master
git pull origin master
git checkout -b code-update

2. Commit
git add .
git commit -m 'Update Code'
git push origin code-update

3. Cleanup
git checkout master
git pull origin master
git branch -d code-update
git push origin :code-update