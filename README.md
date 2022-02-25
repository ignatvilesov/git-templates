# git-templates

Provides some useful templates for daily git workflow.

## Git default commit message

To set a default template for git commit message please use the following command:

```bash
git config --global commit.template PATH_TO_THE_REPO/.gitmessage
```

## Pull request template

To set a default pull request template on GitHub please copy `.github/pull_request_template.md` into `YOUR_REPOSITORY/.github/pull_request_template.md`.

## Inspired by

1. [Using Git Commit Message Templates to Write Better Commit Messages](https://gist.github.com/lisawolderiksen/a7b99d94c92c6671181611be1641c733)
2. [Conventional Commits 1.0.0](https://www.conventionalcommits.org/en/v1.0.0/#summary)
3. [Contributing to Angular](https://github.com/angular/angular/blob/22b96b9/CONTRIBUTING.md#-commit-message-guidelines)
