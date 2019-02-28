# Banno Git Scripts

Here's a collection of Git scripts that help with development at Banno.

* `git-find-issues` finds TODOs with accompanying GitHub issues
* `git-jenkins` opens the Jenkins job associated with the GitHub pull request for the current branch
* `git-openpr` opens the GitHub pull request for the current branch

## Usage

1. Set your `GITHUB_OAUTH_REPO_TOKEN` environment variable.
2. Install Bundler, e.g. `gem install bundler`.
3. Put the script on your path, and make it executable.
4. Call the appropriate `git` command, e.g. `git jenkins`, `git openpr`, etc.