# html-lint mirror

Mirror of html-lint package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For html-lint: see https://github.com/deezer/html-linter


### Using html-lint with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/gisce/pre-commit-html-lint
        sha: ''  # Use the sha you want to point at
        hooks:
        -   id: html-lint
