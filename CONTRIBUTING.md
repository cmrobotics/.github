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

## Commits

A well-crafted Git commit message is the best way to communicate context about a change to other developers working on that project, and indeed, to your future self.

Have you ever tried running git log on one of your old projects to see the "weird" commit messages you have used since its inception? It can be hard to understand why you made some changes in the past, and you'll wish you read this article earlier :).

Commit messages can adequately communicate why a change was made, and understanding that makes development and collaboration more efficient.

- A commit message should summarize what changes were added.
  - If you can summarize in less than 50 characters: use `git commit -m "Description..."`
  - If you can't summarize in less than 50 characters: use `git commit -m "Subject" -m "Description..."` with the a subject around 50 characters and a description around 72 characters.

Here, we will use [Tim Pope's template for good commit messages](https://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html):

```plaintext
Capitalized, short (50 chars or less) summary

More detailed explanatory text, if necessary.  Wrap it to about 72
characters or so.  In some contexts, the first line is treated as the
subject of an email and the rest of the text as the body.  The blank
line separating the summary from the body is critical (unless you omit
the body entirely); tools like rebase can get confused if you run the
two together.

Write your commit message in the imperative: "Fix bug" and not "Fixed bug"
or "Fixes bug."  This convention matches up with commit messages generated
by commands like git merge and git revert.

Further paragraphs come after blank lines.

- Bullet points are okay, too

- Typically a hyphen or asterisk is used for the bullet, followed by a
  single space, with blank lines in between, but conventions vary here

- Use a hanging indent

If you use an issue tracker, add a reference(s) to them at the bottom,
like so:

Resolves: #123
```

## We Develop with Github
We use github to host code, to track issues from public repositories and feature requests, as well as accept pull requests. We use Jira for private repositories.

## We Use [Github Flow](https://docs.github.com/en/get-started/quickstart/github-flow), So All Code Changes Happen Through Pull Requests
Pull requests are the best way to propose changes to the codebase (we use [Github Flow](https://docs.github.com/en/get-started/quickstart/github-flow)). We actively welcome your pull requests:

1. (You're an external collaborator): Fork the repository.
2. Create your branch from the default branch (`master`, `galactic-devel`).
3. If you've added code that should be tested, add tests.
4. If you've changed APIs, update the documentation.
5. Ensure the test suite passes.
6. Format your code using tools from [the Coding Style section](#use-a-consistent-coding-style).
7. Make sure your code lints.
8. Issue that pull request!
9. You need 2 approvals for the merge to be possible. All checks must pass as well.
10. You'll need to rebase your changes on top of the target branch for the merge to be possible.
11. All conversations from the review must be resolved (shows that you've taken them into account) before merging.
12. If you're an internal collaborator, your branch will be deleted when merged.

## Use a Consistent Coding Style

* We follow PEP-8 and PEP-20 for all languages.
* Format your code using 
    * [astyle](https://manpages.ubuntu.com/manpages/trusty/man1/astyle.1.html) for C/C++ using `astyle --style=linux --pad-oper --recursive --indent=spaces=2 --suffix=none [FILE1] [FILE2]`
    * [black](https://www.freecodecamp.org/news/auto-format-your-python-code-with-black/#:~:text=To%20format%20more%20than%20one,black%20folder_name%2F%20in%20the%20terminal.) for Python using `black [FILE]`
