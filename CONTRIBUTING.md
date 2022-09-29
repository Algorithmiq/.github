# Contributing to Algorithmiq

The following are guidelines and suggestions for contributing to Algorithmiq's repositories.

## Getting started

Please see our [website](https://github.com/Algorithmiq) for a brief overview of our projects.

### Asking Questions

Questions come up. We strive to have helpful documentation, but it's unlikely to
have all the answers. If you have a question, please search the documentation
and the GitHub issues for answers. If you can not find the answer then feel free
to open a GitHub issue with the question, using the "Question" template.


## Ways to Contribute

### Reporting Bugs

We use GitHub's issue feature for bug tracking in our repositories. If you think
you have found a bug please first search the issues to see if it has already
been reported. If not, feel free to open a new issue using the "Bug report"
template.

### Suggesting Features

We're happy to consider implementing new features.  Just be aware: we may have
other, more pressing priorities to attend to first.  Like bugs, we use GitHub's
issue feature for tracking feature requests. Please do a quick search to make
sure someone else hasn't already suggested the feature before opening a new
issue using the "Feature request" template.

### Contributing Code

If you want to contribute code to an Algorithmiq project go ahead and open a pull
request (PR). We recommend you first create a draft PR explaining what you are
going to do. This gives our team a chance to provide feedback and help
throughout the process. We welcome contributions to any part of our projects,
not just source code.

Please make sure your PR follows our [coding conventions]().

#### Contribution workflow

This section describes how to get your contributions merged into our repositories.
The procedure for contributing code is **exactly the same** for the core
development team and for external contributors:

* Maintainers do not push directly to the `main` branch of *any* repository.
* Maintainers do not review their own patches.
* Approval of one or more maintainers is sufficient for trivial patches, such as
  typos and trivial bugfixes.
* For any patch that is not trivial, two maintainers need to review and approve
  the patch.

Finally, we do not require any formal copyright assignment or contributor
license agreement. Any contributions intentionally sent upstream are presumed
to be offered under terms of the [choose license]()

##### Getting Started

* Make sure you have a [GitHub account](https://github.com/signup/free).
* [Fork](https://help.github.com/articles/fork-a-repo/) the repository on GitHub.
* On your local machine,
  [clone](https://help.github.com/articles/cloning-a-repository/) your fork of
  the repository.

##### Making Changes

* Add some really awesome code to your local fork.  It's usually a [good
  idea](http://blog.jasonmeridth.com/posts/do-not-issue-pull-requests-from-your-master-branch/)
  to make changes on a
  [branch](https://help.github.com/articles/creating-and-deleting-branches-within-your-repository/)
  with the branch name relating to the feature you are going to add.
* When you are ready for others to examine and comment on your new feature,
  navigate to your fork on GitHub and open a **Draft** [pull
  request](https://help.github.com/articles/using-pull-requests/) (PR). Note that
  after you launch a PR from one of your fork's branches, all
  subsequent commits to that branch will be added to the open pull request
  automatically.  Each commit added to the PR will be validated for
  mergeability, compilation and test suite compliance; the results of these tests
  will be visible on the PR page.
* If you're providing a new feature, you must add test cases and documentation.
* When the code is ready to go, make sure you run the full or relevant portion
  of the test suite on your local machine to check that nothing is broken.
* When you are confident your code is ready to be considered for merging, remove the **Draft** status from your pull request.
  The code will not be merged until:
  - the continuous integration passes, and
  - multiple core developers give "Approved" reviews.

###### Additional Resources

* [General GitHub documentation](https://help.github.com/)
* [PR best practices](http://codeinthehole.com/writing/pull-requests-and-other-good-practices-for-teams-using-github/)
* [A guide to contributing to software packages](http://www.contribution-guide.org)
* [Thinkful PR example](http://www.thinkful.com/learn/github-pull-request-tutorial/#Time-to-Submit-Your-First-PR)


## Code of Conduct

All interactions with the Algorithmiq organization are governed by our
[Code of Conduct](https://github.com/Algorithmiq/.github/blob/main/CODE_OF_CONDUCT.md).


## Acknowledgments

This file is based heavily on Atom's
[CONTRIBUTING.md](https://github.com/atom/atom/blob/master/CONTRIBUTING.md)  and
XCFun's
[CONTRIBUTING.md](https://github.com/dftlibs/xcfun/blob/master/.github/CONTRIBUTING.md).
