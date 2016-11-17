# BonnyCI Project
This is a project to create and run a better breed of CI systems. More information coming soon!

## How Code
We believe in Open Source and open infrastructures. To that end, all the code we develop will be open sourced (aside from any runtime credential secrets). We will maintain a set of repositories within the BonnyCI namespace here on GitHub.

We believe stronly in automation, and infrastructure as code. If we cannot automate it, we do not want it. We've chosen Ansible as our automation engine.

Code change requests are presented as GitHub pull requests. We ask developers to create personal forks of the repository they wish to change in order to commit their changes to their own feature branch, then open a pull request to the BonnyCI repository.

Code testing is currently managed by Travis (yes, we see the irony), and while currently simple, will grow to be more complex in the future. Our goal though is that tests should be reproducable outside of the CI system to aid in developers presenting well tested changes.

Pull requests can be reviewed by anybody, but require an Approval by a member of the BonnyCI Captians team. We prefer small changes using commits that produce a functional tree with every commit, to aid in future bisect adventures.

It is not necessary to create an issue or produce a spec/blueprint, or ask for permission to change something before presenting code. Code can be shared to start and frame a conversation. We do ask that code that is not ready for inclusion be marked in the pull request subject (not the commit message) with `[WIP]`. If the pull request aims to resolve an open issue, please indicate that with a line in the commit message such as `Fixes #XXX`. Additionally, we ask that commit messages be concise and informative. Please follow the guide at http://chris.beams.io/posts/git-commit/ .

### Style Guide
There will be a style guide in the future.

## Where we communicate
In the spirit of openness, we have created an open IRC channel on Freenode, `#BonnyCI`. We welcome all, but ask that you be respectful of others.

We also use issues to record defects and work that should be done in the future. Issues specific to a certain repo should be filed with that repo. Issues that are more project wide should be filed within the [Project Management] (https://github.com/BonnyCI/projman) repository.
