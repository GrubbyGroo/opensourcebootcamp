# Commit Changes

This recipe will guide you to commit your changes and push them up to Github.

1. Make sure you're on the right branch
   1. Type: `git branch`
   1. This will indicate with an astricks what branch is currently checked out
   1. If it's an incorrect branch go ahead switch over to the correct branch
   1. Type: `git checkout <insert the branch name here>`
1. Make sure you have changes to commit
   1. Type: `git status`
   1. All change that are not being tracked should appear in red
1. If there are changes to track let's add it to Git tracking
   1. Type: `git add .`
   1. The period just adds everything
   1. By adding a specific file you can limit what is being tracked
1. Make sure files are being tracked
   1. Type: `git status`
   1. Tracked files should appear in green
1. Commit the changes
   1. Type: `git commit -m "<insert a comment here>"`
   1. Make sure you include your comment in double quotes
   1. Always make sure that the comment makes sense
   1. All comments should relate to what is being checked in
1. Once again, check the status
   1. Type: `git status`
   1. The message should indicate that you're now working on a clean branch
1. One final step! Push the changes to Github
   1. Type: `git push origin HEAD`
   1. Make sure that HEAD is all caps
   1. This will instruct Github to create the branch on the server during the push

That's all! You're now ready to continue working on the current branch. If the feature is complete make sure you create a new branch before starting development on the next feature.
