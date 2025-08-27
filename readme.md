git reset filename

git add .

git init

git status

git add filename

git diff

<!-- revert changes -->

git reset --hard <hashcode>
git revert <hashcode>

git log
git log --oneline

git show code

git checkout -b "branchname"

git branch

git merge branchname

<!-- delete branch -->

git branch -d branchname
git branch -D branchname (unmerged also)

<!-- ESC:wq --> helpful (Escape the writing mode ,save and quit)
<!-- i:insert mode -->

<!-- how to change branchname -->

git branch -m <branchname>

<!-- Git stash -->

allows you to temporarily save your uncommittedchanges (both staged and unstaged) in a "stash"
and revert your working directory back to the last commit

<!-- git stash -->
<!-- git stash list-->
<!-- git stash apply-->
<!-- git stash apply stash@{1}-->
<!-- git stash clear-->

<!-- wworking with github -->
<!-- git remote add origin
    git branch -M main
    git push -u origin main-->

     <!-- git pull origin main -->
     <!-- git pull --rebase origin main -->

     <!-- git branch -r  -->
     <!-- git push origin --delete feature -->
