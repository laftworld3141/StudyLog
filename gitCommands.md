

#Git menual
https://git-scm.com/book/ko/v1/%EC%8B%9C%EC%9E%91%ED%95%98%EA%B8%B0
http://marklodato.github.io/visual-git-guide/index-ko.html








# Add 'upstream' repo to list of remotes
git remote add upstream https://github.com/UPSTREAM-USER/ORIGINAL-PROJECT.git

# Verify the new remote named 'upstream'
git remote -v


git log --graph --oneline
git tag apple
git log --decorate

gitk

git ls-remote [remote]
git remote show [remote]

echo "abcde" > abc.myfirstcode
git add abc.myfirstcode
git status
"abc">>abc.myfirstcoode
gitcommit -m "second commit"
git log
git push "123.4.5.3" branch-name
git pull "12.3.3.2" branch-name

git checkout
git branch
git checkout -b "Chadrick"
git reset 2ndfile

git diff HEAD^
git diff HEAd~4


git checkout -b "new" //checkout and making branch

git merge Chadrick
git branch -D Chadrick
git add .

git remote add susan https://

git push --set-upstream origin work1

git rebase -i
commit --amend
git rebase -i

#View all branches, including those from upstream
git branch -va


# Checkout your master branch and merge upstream
git checkout master
git merge upstream/master

vim .git/config
