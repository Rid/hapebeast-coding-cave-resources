# Contributing Guidelines

Please note that this project is released with a [Contributor Code of Conduct](code-of-conduct.md). By participating in this project you agree to abide by its terms.

## Adding Resources to the List

Please open a pull request (PR) to the `main` branch with your proposed changes to README.md made to your forked repository. [Here](https://gist.github.com/MarcDiethelm/7303312) is a guide to how to do this.

Please include a brief description of what you changed as the description of the PR.

Once your PR is ready, please request a review from me (`@donutboy929`).

## Checks

Your pull requests (PR) will have to pass the following checks before they can be merged.

### Markdown Linter

The README.md file should abide by [these rules](https://github.com/DavidAnson/markdownlint/blob/main/doc/Rules.md), except for MD013 (line length) because GitHub and most IDEs will wrap text.

If you would like to remove a rule from the check, please provide valid reasoning in your PR.

### Link Checker

Extracts links from markdown texts and checks whether each link is alive (`200 OK`) or dead. This repository uses [markdown-link-check](https://github.com/tcort/markdown-link-check).

To exclude links from the markdown link checker, use the following line directly above the line that throws the link error:

```markdown
<!-- markdown-link-check-disable-next-line -->
```

Please do not use this on your initial pull request. You should only add it if your PR fails the markdown link check.
