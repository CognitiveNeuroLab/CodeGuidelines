# Code Guidelines

This document describes basic principles for maintaining and collaborating on code for the CNL labs. These guidelines are intended to ease maintenance of code across multiple individuals the lab and ease the burden of collaborative maintenance of code. Some aspects of this document may not be applicable to a project, such as collaborative guidelines for individual projects (e.g., code made public alongside a publication).

## Community Standards

All interactions must follow the [community standards](CODE_OF_CONDUCT.md).

## Beginners Start Here

[Git](https://git-scm.com/) is the standard tool for [version controlled](https://en.wikipedia.org/wiki/Version_control) collaboration. Once installed, Git may be directly used through a command window or throw a graphic user interface (GUI) such as [GitHub Desktop](https://docs.github.com/en/desktop/contributing-and-collaborating-using-github-desktop/making-changes-in-a-branch/managing-branches-in-github-desktop). Most code editors also provide some level of support for git, such as [VSCode](https://code.visualstudio.com/). 

The basic principles and terminology behind working with git version controlled systems is the same, no matter the tools you use to interact with git. In addtion the previously linked Git manual, the following may serve as helpful reference material while getting started.

* [Repositories](https://docs.github.com/en/repositories): a version controlled project that is often represented as a dedicated directory on one's computer. This is the "CodeGuidelines" repository.

* [Pull Requests](https://docs.github.com/en/pull-requests): formal method for proposing a change to existing code. Prior to a pull request one must either [fork](https://docs.github.com/en/get-started/quickstart/fork-a-repo) a repository or if one owns it, it may be [branched](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches).

The most common format for communicating throughout this process is [Markdown](https://commonmark.org/), a plain text format.

## Repository guidelines

All repositories should have a "README.md" file, providing at least a description of the repository's purpose.

If the repository contains code used by multiple people throughout CNL it is _highly_ recommended that the repository establish standards for the following:

* Unit tests

* Documentation

* Code comments

* Style guide

If you responsible for maintaining a repository and you are leaving the lab you _MUST_ ensure others have author rights to the repository before leaving.


## Pull request guidelines

Once a repository is in use by more than one person these guidelines apply:

* All changes to code should be done via PR not by pushing to the master/main branch of a repository.

* All PRs must be approved by at least 1 reviewer prior to merging.

* Authors should not approve and merge their own PR

* The reviewer of a PR does not have merge rights.

* PRs should be compatible with the repository's standards (unit tests, documentation, code comments)

* **Help! My PR broke everything!**: Simply make efore any other PRs go through be sure to make another PR.


##
