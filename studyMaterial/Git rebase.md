git-rebase - Reapply commits on top of another base tip

The goal of a rebase is to change the start (or base) of a branch. So, instead of the branch starting from the original point (ie: commit 2 “E”) you’re bringing it forwards or backwards to a different point in time.

Assume the following history exists and the current branch is "topic":

	         A---B---C topic
	        /         
       D---E---F---G master


From this point, the result of either of the following commands:

git rebase master
git rebase master topic


would be:

                      A'--B'--C' topic
                     /
        D---E---F---G master

Bibliography: https://git-scm.com/docs

https://medium.com/swlh/squash-and-rebase-git-basics-5cb1be1e0dac