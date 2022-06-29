# Contributing
:+1::tada: First off, thanks for taking the time to contribute! :tada::+1:

The following is a set of guidelines for contributing to DirectShapeFramework. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

## Table Of Contents

Issues are created [here](https://github.com/electron/electron/issues/new).
For submitting pull request go [here](### Submitting a pull request)

## How Can I Contribute?

### Reporting Bugs
This section guides you through submitting a bug report for DirectShapeFramework. Following these guidelines helps maintainers and the community understand your report :pencil:, reproduce the behavior :telescope:, and find related reports :mag_right:

We are using [GitHub Issues](https://guides.github.com/features/issues/) for creating Bug reports.
Before creating a new Issue, please check [Opened Issues](https://github.com/PalbestGit/oss-enterprise/issues) and [Closed Issues](https://github.com/PalbestGit/oss-enterprise/issues?q=is%3Aissue+is%3Aclosed).

> **Note:** If you find a **Closed** issue that seems like it is the same thing that you're experiencing, open a new issue and include a link to the original issue in the body of your new one.

If you have found a new bug, [create a new Issue](https://github.com/electron/electron/issues/new).

#### How To Submit A (Good) Bug Report?

Explain the problem and include additional details to help maintainers reproduce the problem:

> **Use [Bug] prefix** in the Issue Title to help others identify this Issue as a Bug

* **Create a single Issue for single bug** Do not enumerate multiple bugs or feature requests in the same issue.
* **Use a clear and descriptive title** for the issue to identify the problem.
* The more information you can provide, the more likely someone will be successful at reproducing the issue and finding a fix.
* **Include screenshots or animated GIFs** which show you following the described steps and clearly demonstrate the problem.
* **If possible, attach the Revit project in which the bug occurred**

### Suggesting Enhancements

We are using [GitHub Issues](https://guides.github.com/features/issues/) for Suggesting Enhancements.
Before creating a new Issue, please check [existing Issues](https://github.com/PalbestGit/oss-enterprise/issues). If somebody already suggested similar idea support it by adding a comment with :+1: or explain why it should be added ASAP.

> **Use [Add] prefix** in the Issue Title to help others identify this Issue as Suggesting Enhancements

### Submitting a pull request

#### Algorythm of proposing by Pull Request:
1. [Fork][fork] and clone the repository [Only for the first time](https://docs.github.com/en/get-started/quickstart/fork-a-repo)
1. Create a new branch
1. Make your changes and ensure that your feature works stable
1. Read this [Suggestions](#### Suggestions to make a good Pull Request)
1. Push to your fork and [submit a pull request][pr]
1. Wait for your pull request to be reviewed and merged.

#### Suggestions to make a good Pull Request

In general, commits [should be atomic](https://en.wikipedia.org/wiki/Atomic_commit#Atomic_commit_convention) and diffs should be easy to read. For this reason, do not mix any formatting fixes or code moves with actual code changes.

Commits should be named according to [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

Make sure each individual commit is hygienic: that it builds successfully on its own without warnings, errors, regressions, or test failures.

Commit messages should be verbose by default consisting of a short subject line (50 chars max), a blank line and detailed explanatory text as separate paragraph(s), unless the title alone is self-explanatory (like "Correct typo in init.cpp") in which case a single title line is sufficient. Commit messages should be helpful to people reading your code in the future, so explain the reasoning for your decisions. Further explanation here.
