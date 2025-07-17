# Review 17th,Jul
- Using '.gitignore', I've only committed "b.txt" except a.txt and c.txt
- When you want to cancel the file added in the staging area, please use 'git restore --staged'.
- Use 'revert' when you record a commit for the cancellation.
- Far from 'revert', 'reset' is for deleting all the information in commit list.

 Today's comment: There were conflicts when using 'git reset --hard'. Since the discrepancy arose between the local and the remote repositories, I've resolved this problem with AI tool by using * git push --force --set-upstream origin master **. This is not recommended because it may cause confusion with the teammates.
