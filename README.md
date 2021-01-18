# Financial Goals
This tool is not for everybody. I created it to help smooth my personal
finance workflow. If it is useful to you, then that is a pleasant surprise to
me.

## Setup
If you are seeing this README, then you are on a branch that currently doesn't
have much of anything. Try taking a look at the other branches in the repo.

## Contribution Guidelines
If you have ideas for improving this script, I welcome both opening an issue on
GitHub or even a PR with the suggested improvement. If you do open a PR, I ask
that you conform to the following guidelines:

### Coding Style
For all contributions, I ask that PEP-8 be followed with the exception that
I'm okay with lines up to 120 characters long.

### Workflow
For the most part, I use the Git Flow workflow. For your forks, obviously, it
doesn't really matter what workflow you use, but I do ask that you:
- sign your commits,
- squash commits before opening a PR, and
- keep changes as incremental as reasonably possible. I find it acceptable to
  implement features over the course of multiple PRs and I promise I won't get
  annoyed if you do that.

### Commit Messages
The rules of [conventional commit
messages](https://www.conventionalcommits.org/en/v1.0.0-beta.2/) should be
observed. Observe to keep the first line of the commit message down to 50
characters and insert hard line-breaks at 72 characters for the rest of the
message body.

When working on `feature`, `bugfix` or `hotfix` branches, the rules can be
relaxed a bit. PRs should only be opened from your `develop` branch, and when
wrapping up your `feature` branches, you should squash your commits.

#### Tags
  - fix&mdash;for bugfixes
  - feat&mdash;for any new functionality
  - BREAKING CHANGE&mdash;annotation in the commit message body for any changes
    that will affect backwards-compatability.
  - refactor&mdash;for reworked code that ends up being functionally the same
  - docs&mdash;for changes to docstrings, CHANGELOG.md, this README, etc.
  - chore&mdash;for changes to the repo that don't affect functional code or
    docs (i.e. Makefiles, Dockerfiles, etc.)
