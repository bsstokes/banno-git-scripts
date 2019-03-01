# Banno Git Scripts

## Git Scripts

* [`git-find-issues`](git-scripts/git-find-issues) finds TODOs with accompanying GitHub issues.
* [`git-jenkins`](git-scripts/git-jenkins) opens the Jenkins job associated with the GitHub pull request for the current branch.
* [`git-open-pr`](git-scripts/git-open-pr) opens the GitHub pull request for the current branch.

### Usage

1. Set your `GITHUB_OAUTH_REPO_TOKEN` environment variable.
2. Have Ruby installed. (You're on your own there.)
3. Install [Bundler](https://bundler.io/), e.g. `gem install bundler`.
4. Put the script on your path, and make it executable.
5. Call the appropriate `git` command, e.g. `git jenkins`, `git open-pr`, etc.

## Git Hooks

* [`pre-commit-nocommit`](`git-hooks/pre-commit/pre-commit-nocommit`) prevents committing code with `NOCOMMIT` in it.

### Usage

1. Copy these into your project's `.git/hooks` directory.
2. Make them executuable.

