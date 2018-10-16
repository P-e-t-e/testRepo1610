# testRepo1610
Repo for testing git


Guide to contributing to github projects

1. Find suitable project
2. Fork project to your own account
3. Clone project from your account using $git clone [link]
4. Config your email using $git config user.email [your_email]
5. Let git know about upstream (original project repo) using $git remote add upstream [https://github.com/OGCreatorUsername/OGrepo].git


Origin will be your account, upstream will be the OG repo which you cannot write to (according to our config).

6. Make a branch (We want to keep master as a backup), do this using $git checkout -b [feature-branch-name] (-b notes that we want to create a branch)

7. Make whatever changes you want to the code

8. Add files using $git add [filename]
9. commit the changes with $git commit -m "[commit message]"

..changes are now saved only on the feature branch on the local machine

10. Push changes to OUR repo using $git push origin [feature-branch-name]

11. Go onto github and create pull request, wait for OGCreator to accept request

12. IF FEATURE ACCEPTED Get local master branch up to date with master using $git checkout master && $git pull upstream master

13. Cleanup - delete branch on your github account, on pc run $git branch -D [feature-branch-name]

14. IF FEATURE NEEDS FIXING go to stage 7.
