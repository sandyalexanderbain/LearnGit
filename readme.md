## Welcome, Git.
This is coming from "dev-alexander"
Coming from the "dev-jsm" branch.

I'm adding this from "feature-branch"


Push a remote branch upstream.
git push --set-upstream origin BRANCH_NAME
or 
git push -u origin BRANCH_NAME

Push changes after a branch is established.
git push


Typical workflow to follow when working on a team with Git.
1. Clone the repository.
2. Create a new branch from the main branch or another branch.
3. Make your changes.
4. Push the branch to the remote repository.
5. Open up a pull request. 
6. Merge the changes.
7. Pull the marged changes into your local main branch.
8. Repeat from step 2.

How to deal with merge conflicts:
1. Go to main branch.
2. Pull changes from one approved merge request.
3. Go to your branch.
4. Merge with "git merge main"
5. See merge conflict error and go back to main branch.
6. Fix changes manually in file.
7. Stage and Commit changes.
8. Push changes.
