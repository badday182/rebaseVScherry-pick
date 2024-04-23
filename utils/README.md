# How to do rebase

# Second section

# New section in doc

# One more section

# New section for Valera

# yet enother section



# Statement

## Hashes
on merge hashes of commits remind same
and on rebase hashes recreates with new hashes

maybe for cherry-pick also it recreates


main
branch from main
new commit in feature
new commit in feature
push feature branch to remote
new commit in main
rebase main in to feature
force push

expected new hashes in feature

reprodused!


+ main
+ branch from main
+ new commit in feature
+ new commit in feature
+ push feature branch to remote
+ new commit in main (divergency main and feature branch)
+ marge main in to feature
+ push

+ main
+ branch from main
+ new commit in feature
+ push feature branch to remote
+ new commit in main
+ new commit in feature
+ new commit in main
+ marge main in to feature
+ push
pull request rebase merge

expected new same hasher in feature


git log and commits in github show commits in order of commit date
not it order of legassy (parrent/child) relations

local rebase give different result than github rebare

we add 3rd commit to main before rebase to main feature branch

in github it take all commits from main without changes
and recreate all commits from feature branch with new hashes
and remeve marge commit from feature branch

in local rebase
it take all commits from feature without chang
put it in to main
and recreate last 3rd commit in main with new hash






# Author
in case whet I make rebase of bunch of commit created by other person
what information are remain in resul brunch?
is information about author remain or revrite?
or just creating same conten in new commits with new hashes?


main
branch from main
new commit in feature one person
new commit in feature one person
push feature branch to remote
pull feature, second person
new commit in main
rebase main in to feature second person
force push

# Cascade marge

if on merge commit hashes remains same
check if it true on merge sub featur in to feature and then feature in to main


main
branch from main
new commit in feature one person
new commit in feature one person
push feature branch to remote
pull feature, second person
new commit in main
rebase main in to feature second person
force push



# fast forward
asumption that ff insert commit betwin main comits
and recreate last (head) commit with new hash

to do: make marge with different approach and note the difference






cherry-pick

main 
new branch ch1 and ch2
new four commit to ch1
cherry-pick defoult
cherry-pick edit
cherry-pick no-commit
cherry-pick signoff





last main 
checkout -b ch3
git reset --hard HEAD~10 
chirry-pick commit 1
chirry-pick 4
chirry-pick 8

