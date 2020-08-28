Create a New Branch in Local

Create a new branch called test using the following command:

$ git branch test

This command creates the test branch.

We are still in the context of the master branch. In order to switch to the test branch. use the following command:

$ git checkout test

Now we are in the test branch.

You can list out all the branches in local using the following command:

git branch


Do Some Commits in the New Branch

Modify demo.txt by adding the following snippet:

>Initial Content 
>Adding more Content 
>Adding some Content from test Branch

Now stage and commit using the following commands:

$ git add demo.txt 

$ git commit -m "Test Branch Commit"

This commit was done in the Test Branch, and now Test Branch is ahead of Master Branch by 1 commit — as the test branch also includes the 2 commits from the master branch.

You can verify the commit history in Test Branch using:

git log