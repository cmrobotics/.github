# Contributing to Coalescent Mobile Robotics
We love your input! We want to make contributing to this project as easy and transparent as possible, whether it's:

- Reporting a bug
- Discussing the current state of the code
- Submitting a fix
- Proposing new features
- Becoming a maintainer

## Branch naming
All branches should follow the pattern `prefix/descriptive-name-separated-by-dashes`, where the `prefix` must be selected from the list below.

 - `feature`: when introducing a new feature.
 - `bugfix`: when solving a bug.
 - `hotfix`: when solving a critical bug that should be pushed to production asap.
 - `refactor`: when refactoring the code without introducing feature or fixing bugs.

 The prefixes reflect that you should try, as much as possible, to separate the concerns of your PR. If you are introducing a feature and you find bugs,
 please open another PR to address their solution instead of combining both changes in the same PR.
## We Develop with Github
We use github to host code, to track issues from public repositories and feature requests, as well as accept pull requests. We use Jira for private repositories.

## We Use [Github Flow](https://docs.github.com/en/get-started/quickstart/github-flow), So All Code Changes Happen Through Pull Requests
Pull requests are the best way to propose changes to the codebase (we use [Github Flow](https://docs.github.com/en/get-started/quickstart/github-flow)). We actively welcome your pull requests:

1. Fork the repo and create your branch from the default branch (`master`, `galactic-devel`).
2. If you've added code that should be tested, add tests.
3. If you've changed APIs, update the documentation.
4. Ensure the test suite passes.
5. Make sure your code lints.
6. Issue that pull request!
7. You need 2 approvals for the merge to be possible. All checks must pass as well.
8. You'll need to rebase your changes on top of the target branch for the merge to be possible.
9. All conversations from the review must be resolved (shows that you've taken them into account) before merging.

## Use a Consistent Coding Style

* We follow PEP-8 and PEP-20 for all languages.
* You can use VSCode extensions to format your code.
