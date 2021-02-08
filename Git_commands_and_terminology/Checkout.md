# Checkout:

A git checkout command will allow for the navigation between branches created by git branch. Checking out a branch updates the files in the working directory to match the version stored in that branch, and it tells Git to record all new commits on that branch.

A checkout is an operation that moves the HEAD ref pointer to a specified commit. To demonstrate this consider the following example.

![](Before_checkout.png)

This example demonstrates a sequence of commits on the master branch. The HEAD ref and master branch ref currently point to commit d. Now let us execute git checkout b

![](After_checkout.png)

This is an update to the "Commit History" tree. The git checkout command can be used in a commit, or file level scope. A file level checkout will change the file's contents to those of the specific commit.
