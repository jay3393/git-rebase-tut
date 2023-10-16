# git-rebase-tut
Learning how git rebase works

This is feature 1.0 initial commit
- in development branch for this feature, adding some changes
- Assuming someone made some changes to this file and committed and pushed to feature-1.0
- outside user made another change...
- at the same time, locally i made some changes...
- i commit locally without pulling first!!!
- outside user made a third change!!!

This is feature 1.1 initial commit
- outside user makes 1 commit
- outside user makes 2 commits
- oautside user makes 3 commits
- locally i am making changes while my teammates already committed 3 times
- let's try rebasing to make sure that we get the changes and apply our local changes on top of that
- but before rebasing, we want to commit our local changes without fetching/pulling