#### Delete all commits of a Repository

Deleting the .git folder may cause problems in your git repository. If you want to delete all your commit history but keep the code in its current state, it is very safe to do it as in the following:

Checkout

```git checkout --orphan latest_branch```
<br><br>

Add all the files

```git add -A```
<br><br>

Commit the changes

```git commit -am "commit message"```
<br><br>

Delete the branch

```git branch -D main```
<br><br>

Rename the current branch to main

```git branch -m main```
<br><br>

Finally, force update your repository

```git push -f origin main```
<br><br>

PS: this will not keep your old commit history around
