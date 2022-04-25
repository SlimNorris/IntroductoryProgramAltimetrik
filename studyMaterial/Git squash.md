With rebasing you’re creating a nice chain of commits tracing right back to the start, but, after a while, it can get quite long. 

With “squash”, you can merge all of your commits from a feature branch into a single commit, which can then be added to the end of the main branch.


Pre-Merge:

          A---B---C topic
         /
    D---E---F---G master

Post-Merge:

          A---B---C topic
         /         \
    D---E---F---G---H master

Post-Rebase:

                  A'---B'---C' topic
                 /
    D---E---F---G master

Post-Rebase and Squash:

                  A* topic
                 /
    D---E---F---G master

A* equals to A'--B'--C'

Bibliography: https://git-scm.com/docs
https://medium.com/swlh/squash-and-rebase-git-basics-5cb1be1e0dac