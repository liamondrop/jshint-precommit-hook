jshint-precommit-hook
=====================

Automatically lint your staged .js files on git commit (requires jshint)

*Note that this will likely only work via command line.*

Add the `pre-commit-jshint` file to `.git/hooks/` and rename to `pre-commit`. Make sure file is executable (`chmod +x .git/hooks/pre-commit`)

An alternative and probably better option is to break out each of your pre-commit hooks into individual files and combine them a la: https://github.com/githubbrowser/Pre-commit-hooks 

