# Git WIP Brach Workflow

I personally don't prefer to push non-working code. (Or, to be fair, code that I know doesn't work!) But sometimes people like to see my latest code and 
sometimes people like to see that those green boxes are being filled 🙄... I would normally consider a rebase workflow that would allow me to squash a
bunch of WIP commits into a single commit before I do a PR. But some places are not okay with rewriting history. 

Because of that, I've decided that it might be beneficial to have a workflow that would use WIP branches that then rebase into a feature branch. From
there, I can use the feature branch to hold only individual commits in which some subset of that feature that has properly linted code, code that builds,
and tests that pass. For small features, this is probably overkill, but for larger features, this will surely make my overall progress more visible and
more trackable.

