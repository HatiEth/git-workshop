Small introductional git workshop.

Presentation is inside the `gh-pages`-Branch


Workshop (master branch) Stages:
+ Clone the repository with `git clone https://github.com/HatiEth/git-workshop.git` (Https da keine Collaboratoren)
+ How to find all branches
+ How to resolve merge conflicts


Additional:
+ You can create a branch using `git branch <branch-name>` and `git checkout <branch-name>` or  `git checkout -b <branch-name>`
+ There is a branch `git-shorthands` which contains some shorthands for git
	+ `bin`
		+ `git-update-from <branch-name>` pulls the given branch, merges it into current branch and commits
		+ `git-publish-to <branch-name>` changes branch to given branch & pulls, merges other into given branch pushes
		+ `git-find-ignored` finds commited ignored files
		+ `gitlog` visualizes git log
	+ `.bashrc`
		+ adds `cwd` to shell, changes directory to last used (every `cd` changes path used by `cwd`)
		+ automatically adds ssh files by pattern `~/.ssh/id_*_rsa`

