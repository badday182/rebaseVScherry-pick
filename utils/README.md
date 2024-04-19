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

main
branch from main
new commit in feature
push feature branch to remote
new commit in main
new commit in feature
new commit in main
marge main in to feature
push
pull request rebase merge

expected new same hasher in feature





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







To child commit

create commit one
create commit two
+ move head to commit one
+ create commit three
observe git tree

in case when we create commit from detached head
from not head commit this new commit remind dangling, and cant be accesseble without direct checkout by hash
